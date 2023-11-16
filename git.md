LES LIGNES DE COMMANDES GIT :

Les lignes de commandes sont saisies dans le terminal GIT BASH, ou celui de VS CODE.

Pour créer un projet dans un quelconque répertoire :
mkdir : elle sert à créer un dossier dans un répertoire de travail
echo > nom_du_fichier : elle sert à créer un fichier
cd : elle permet de changer de répertoire
cd .. : elle permet de revenir sur l'ancien répertoire

---

Pour versionner un projet dans le répertoire GIT :
git init : elle est utilisée pour initialiser un dossier dans le répertoire git
git add nom_du_fichier : elle permet d'ajouter un fichier ou un dossier dans le répertoire git
git add . : elle permet d'ajouter tous les fichiers ou dossiers dans le répertoire git
git commit -m "ecrire_message" : elle permet de sauvegarder une version du projet
git status : elle permet de vérifier l'état du répertoire de travail
git config --global user.name "Votre Nom" : elle sert à configurer le nom d'utilisateur associé au compte GIT
git config --global user.email "votre.email@example.com" : elle sert à à configurer l'e-mail associée au compte GIT

git checkout -b nom_de_la_branche (ou lien_du_commit après l'avoir récupéré avec le git log) : elle permet de créer une nouvelle branche
git checkout nom_de_la_branche : elle permet de changer de branche (par défaut on est dans la branche master)

La lettre "A" apparaît à côté du fichier ou du dossier ajouté.
La lettre "M" apparaît à côté du fichier ou du dossier modifié.

---

SUR GITHUB:
Cliquez sur "your repositories", puis sur le bouton new.
Une page "create new repository" s'affiche. On choisit le nom du dossier repository et on valide le formulaire.
Ensuite on fait copier-coller les trois liens dans le terminal VS CODE ou GIT BASH :

- git remote add origin https://github.com/bsznn/git-exemple.git : elle sert à lier le dépot local au dépot distant
- git branch -M main : elle permet de renommer notre branche principale "main"
- git push -u origin main : elle permet d'envoyer le dépôt local dans la branche "main"

  Un lien qui nous redirige vers le dossier repository apparaît dans le terminal.

---

git push : elle permet d'envoyer un dépot local vers github après avoir utilisé le "git push -u nom_du_fichier"
git clone 'url_du_git': elle permet de cloner un dossier github vers un dépôt local
git log : elle est utilisée pour obtenir la liste des commits effetués
..q : elle sert à quitter la commande précédente

clear : elle permet de nettoyer le terminal (ou enlève toutes les lignes de commande précédentes)

git reset --hard HEAD^ : elle annule le dernier commit et supprime toutes les modifications locales
git reset --soft HEAD^ : elle annule également le dernier commit mais conserve toutes les modifications effectuées dans le répertoire de travail
