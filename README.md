Créer un Google Sheets Scissions — Maison Savary.
Extensions > Apps Script, puis :
coller Code.gs dans le fichier existant ;
+ > HTML, nommer le fichier Index (sans .html), coller Index.html.
Lancer la fonction initialiser() une fois. Autoriser le script quand c'est demandé. Elle crée l'onglet Scissions, l'onglet Référentiel et le dossier Drive des photos.
Copier l'ID du dossier photos affiché dans les logs (Ctrl+Entrée) dans CONFIG.DOSSIER_PHOTOS_ID.
Remplir l'onglet Référentiel : colonne A les clients, colonne B les produits, colonnes C et D les motifs, colonne E les opérateurs. Ce sont les listes du formulaire.
IA (facultatif) : Paramètres du projet > Propriétés du script > Ajouter → nom ANTHROPIC_API_KEY, valeur = ta clé. Sans clé, tout marche, le bouton IA affiche juste un message.
Déployer > Nouveau déploiement > Application web
Exécuter en tant que : moi ;
Accès : utilisateurs de Maison Savary (ou "tous" si tablette partagée sans session Google).
Envoyer l'URL aux opérateurs → "Ajouter à l'écran d'accueil" sur le tel/tablette : ça s'ouvre comme une appli.
