# OpenPublisher

OpenPublisher est une application Windows de publication assistée par ordinateur, en développement actif. Son objectif est de retrouver progressivement les habitudes de travail de Microsoft Publisher, avec une interface native Windows et des documents éditables.

**Aucune version stable n’est actuellement publiée.** Le logiciel ne doit pas encore être considéré comme un remplacement complet de Publisher.

## Fonctionnalités en développement

- Publications multipages, zones de texte enrichi et cadres liés.
- Images, formes, groupes, tableaux et pages maîtres.
- Modèles personnalisables et format natif `.opub`.
- Export PDF avec texte sélectionnable.
- Copies de récupération locales et historique de sauvegarde.

L’import `.pub` est expérimental et peut nécessiter LibreOffice. Les documents Publisher originaux doivent être conservés ; une conversion peut perdre des éléments ou leur mise en forme.

## Installation et mises à jour

Les futurs installateurs validés seront disponibles exclusivement dans les [Releases officielles](https://github.com/Louis-gllt/OpenPublisher/releases). En l’absence de Release, aucun installateur public n’est proposé.

La mise à jour à distance est en préparation. Elle restera désactivée tant que la vérification de l’authenticité des packages et les essais d’installation indépendants ne seront pas validés. Aucun compte GitHub ni outil de développement ne devra être nécessaire pour utiliser les futures versions distribuées.

## Support et confidentialité

Les problèmes peuvent être signalés dans les [Issues](https://github.com/Louis-gllt/OpenPublisher/issues). Indiquez la version du programme, la version de Windows et les étapes permettant de reproduire le problème. Ne joignez pas de publication confidentielle, de document personnel, de clé, de jeton ou de rapport non expurgé.

Les copies de récupération et les diagnostics sont locaux. Ils ne remplacent pas une sauvegarde indépendante de vos documents.

## Distribution et droits

Ce dépôt public est réservé à la présentation et à la distribution du logiciel. Il ne contient pas le code source de développement. Les conditions de distribution, notices de composants tiers et signatures applicables accompagneront les futurs packages ; aucune licence sur le code privé n’est accordée par ce README.

OpenPublisher est un projet indépendant, non affilié à Microsoft. Microsoft Publisher est une marque de Microsoft.

## Canal bêta en préparation

Les futures bêtas utiliseront des installateurs autonomes Windows x64 et un manifeste RSA-4096 signé, vérifié par le logiciel avant installation. La signature du manifeste ne constitue pas une signature Authenticode. La chaîne complète installation puis mise à jour Internet reste à valider. Aucune version n'est annoncée disponible avant sa publication effective dans Releases.

Le workflow de publication de ce dépôt accepte uniquement des tags bêta avec un installateur dont le manifeste correspond à la clé publique de distribution. Il ne compile aucun code source privé et ne publie aucun secret.
