#
description de la page :
Cette page sert à tester un dépôt : la créer, la modifier, puis envoyer chaque changement sur GitHub.

Initialiser le dépôt
Dans le dossier qui contient cette page.

git init
Ajouter le fichier
Prépare index.html pour le premier commit.

git add index.html
Enregistrer un commit
Un commit est une photo de ton projet à cet instant.

git commit -m "Première version de la page"
Relier le dépôt GitHub
Crée d'abord un dépôt vide sur GitHub, puis colle son adresse.

git branch -M main
git remote add origin https://github.com/TON-NOM/TON-DEPOT.git
Envoyer sur GitHub
Ton code est maintenant en ligne.

git push -u origin main