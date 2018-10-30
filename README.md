# gitMemo
==========

GIT
---
git init : transforme un dossier en repository (création de l'index .git)
git add  : ajoute un element à l'index (.git)
git commit -m <comment> : effectue un commit 
|| git commit -a -m <comment>
|| git commit -am <comment>

git status : affiche l'etat du commit
git log    : affiche l'historique des commit
git checkout SHADuCommit : se positionne sur un commit
|| git checkout master   : se positionne sur le dernier commit
|| git checkout <branch> : se positionne sur une branche

git revert SHADuCommit 		: sélectionne un commit, crée son inverse, 
				  puis le place à la téte de la branche
git commit --amend -m "comment" : modifie le commentaire du dernier commit
git reset --hard                : annule toutes les modifs du commit en cours avant commit

git clone <gitHubRepositoryLink.git> : télécharge un nouveau repository depuis github
git remote add origin <gitHubRepositoryLink.git> : upload un nouveau repository vers gitHub 

git push -u origin master : envoi les nouveaux commit au serveur
git pull -u origin master : télécharge les nouveaux commit depuis serveur

git branch : affiche liste des branches
|| git branch <branch> : créer une branche
|| git checkout <branch> : se positionne sur une branche
|| git checkout -b <branch> : créer, puis se positionner sur une branche

BASH
----
ls : lister
cd : parcourir
touch : create file
mkdir : create folder
cat : display file content
rm : delete file
rmdir : delete folder
ctrl + insert  : copier 
shift + insert : coller

VIM
---
i = edit
esc = saisir les commandes vim
:w save
:s quit
:x save && quit


