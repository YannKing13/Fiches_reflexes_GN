RÉFLEXE GN V34 — NOUVEL ONGLET « PERQUISITION »

Cette version reprend la V33 et conserve les autres fonctionnalités (VIN, NATINF, classement des armes, transports et constatations, alcoolémie, stupéfiants, etc.).

NOUVEAUTÉS
- Onglet « 🔍 Perquisition — PV ODT ».
- Deux matrices ODT distinctes, dérivées de deux modèles fournis par l'utilisateur : enquête préliminaire et enquête de flagrance.
- Les tableaux d'en-tête, dimensions, styles et en-têtes des feuillets suivants sont conservés au maximum.
- Toutes les données nominatives et les références de procédures des documents d'origine ont été supprimées des matrices incorporées.
- Formulaire de saisie sur téléphone : procédure, cadre juridique, grade/identité rédacteur, personnes présentes et témoins, assistants, pièces, objets découverts/saisis/scellés, clôture.
- Ajout illimité de pièces, de militaires et d'objets ; chaque objet a un emplacement, une description, une suite donnée et éventuellement un numéro de scellé.
- Possibilité de renseigner une perquisition négative. Les mentions d'assentiment, de scellés et de signatures sont générées UNIQUEMENT d'après des cases ou informations explicitement remplies.
- Prévisualisation textuelle et export d'un fichier .odt modifiable.
- Brouillons sauvegardés localement dans le navigateur (localStorage), sans chiffrement ni partage entre téléphones.

MODE D'EMPLOI
1. Ouvrir l'onglet Perquisition, puis « Nouveau PV de perquisition ».
2. Compléter les sept étapes, notamment les conditions de présence et les références juridiques.
3. Dans la rubrique Pièces, ajouter les pièces/espaces réellement visités.
4. Dans Objets / scellés, décrire chaque découverte ; distinguer « découvert », « saisi » et « simplement constaté ».
5. Vérifier le résumé, puis choisir « Exporter le PV en ODT ».
6. Ouvrir l'ODT dans un traitement de texte compatible, relire et finaliser la procédure.

DÉPLOIEMENT
Décompresser ce ZIP et déposer à la racine du dépôt GitHub les huit fichiers : index.html, sw.js, manifest.webmanifest, les quatre PDF de formulaires existants et README_V34.txt. Les modèles ODT de perquisition sont intégrés dans index.html : aucun fichier supplémentaire à importer.
Après publication, forcer si besoin l'actualisation avec ?v=34 à la fin de l'adresse du site.
Sauvegarder les données locales des anciennes versions avant de remplacer les fichiers.

SÉCURITÉ ET LIMITES
Prototype NON officiel, uniquement avec des données fictives tant qu'une solution professionnelle autorisée n'a pas été validée. Le dépôt GitHub Pages est public et les données localement enregistrées ne sont pas chiffrées par l'application. Le rôle de l'OPJ/APJ, les exceptions, les personnes présentes, les accords/autorités judiciaires et les articles applicables doivent être vérifiés selon le cadre d'enquête et le cas d'espèce.
Aucune signature manuscrite n'est insérée automatiquement dans ces nouveaux PV ODT ; les blocs de signature doivent être complétés dans le traitement de texte / circuit de procédure autorisé.
Les sources ODT transmises servaient uniquement à créer une matrice anonymisée. Il peut subsister des écarts de rendu selon le logiciel ODT utilisé ; contrôle des feuillets et de la pagination indispensable.

TESTS
Syntaxe JavaScript, export ODT positif/négatif, documents multipages et ouverture via LibreOffice vérifiés. Navigation tactile Samsung/iPhone NON vérifiée dans cette session (environnement du navigateur de test bloqué).
