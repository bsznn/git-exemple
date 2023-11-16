LES LIGNES DE COMMANDES GIT :

Les lignes de commandes sont saisies dans le terminal GIT BASH, ou celui de VS CODE.

Pour créer un projet dans un quelconque répertoire :
mkdir : il sert à créer un dossier dans un répertoire de travail
echo > nom_du_fichier : il sert à créer un fichier
cd : il permet de changer de répertoire
cd .. : il permet de revenir sur l'ancien répertoire

Pour versionner un projet dans le répertoire GIT :
git init : il est utilisé pour initialiser un dossier dans le répertoire git
git add nom_du_fichier : il permet d'ajouter un fichier ou un dossier dans le répertoire git
git add . : il permet d'ajouter tous les fichiers et dossiers dans le répertoire git
git commit -m "ecrire_message" : il permet de sauvegarder une version du projet
git status : il permet de vérifier l'état du répertoire de travail
git config --global user.name "Votre Nom" : il sert à configurer le nom d'utilisateur associé au compte GIT
git config --global user.email "votre.email@example.com" : il sert à à configurer l'e-mail associée au compte GIT

La lettre "A" apparaît à côté du fichier ou du dossier ajouté.
La lettre "M" apparaît à côté du fichier ou du dossier modifié.
