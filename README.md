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

Des **préversions bêta expérimentales** sont disponibles dans les [Releases officielles](https://github.com/Louis-gllt/OpenPublisher/releases).

1. Télécharger `OpenPublisher-Setup-x64.exe` depuis la version bêta souhaitée.
2. Exécuter l'installateur Windows et choisir les raccourcis ainsi que l'association `.opub` facultative.
3. Lancer **OpenPublisher** depuis le bureau ou le menu Démarrer.

Windows x64 ; runtime inclus. Aucun SDK .NET, Git, compte GitHub ni dossier de développement n'est nécessaire. Conservez vos publications originales et des sauvegardes indépendantes : aucune version stable n'est encore proposée.

Dans **Fichier → À propos**, choisir Stable ou Bêta et rechercher les mises à jour. Le logiciel utilise uniquement les Releases de ce dépôt, vérifie un manifeste RSA signé et le SHA-256 du paquet avant installation, puis demande confirmation pour fermer les publications. Les premières bêtas servent notamment à valider ce parcours de bout en bout ; aucune validation sur PC vierge n'est encore annoncée.

La signature du manifeste est distincte d'Authenticode. Aucun certificat Authenticode n'est actuellement configuré ; les protections et avertissements Windows restent actifs.

## Support et confidentialité

Les problèmes peuvent être signalés dans les [Issues](https://github.com/Louis-gllt/OpenPublisher/issues). Indiquez la version du programme, la version de Windows et les étapes permettant de reproduire le problème. Ne joignez pas de publication confidentielle, de document personnel, de clé, de jeton ou de rapport non expurgé.

Les copies de récupération et les diagnostics sont locaux. Ils ne remplacent pas une sauvegarde indépendante de vos documents.

## Distribution et droits

Ce dépôt public est réservé à la présentation et à la distribution du logiciel. Il ne contient pas le code source de développement. Les conditions de distribution, notices de composants tiers et signatures applicables accompagneront les futurs packages ; aucune licence sur le code privé n’est accordée par ce README.

OpenPublisher est un projet indépendant, non affilié à Microsoft. Microsoft Publisher est une marque de Microsoft.

