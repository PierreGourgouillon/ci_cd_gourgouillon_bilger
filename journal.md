Création le 27 Mai 2024
Branche 1 le 27 Mai 2024
Second commit sur la branche first-branch

4a070843 (Pierre 2024-05-27 11:34:09 +0200 3) Second commit sur la branche first-branch

4a070843: C'est l'identifiant SHA-1 abrégé du commit
Pierre: C'est le nom de l'auteur du commit
2024-05-27 11:34:09: C'est la date et l'heure à laquelle le commit a été créé.
Second commit sur la branche first-branch: C'est le contenu réel de la ligne dans le fichier à cette ligne précise

---------------------------------------

# HISTORIQUE DES COMMANDES

cd ci_cd_gourgouillon_bilger: Se rendre dans le dossier `ci_cd_gourgouillon_bilger`

touch journal.md: Créer le fichier `journal.md`

touch TODO.md: Créer le fichier `TODO.md`

ls: Lister les fichiers dans le dossier courant

rm README.md: Supprimer le fihier `README.md`

ls: Lister les fichiers dans le dossier courant

git status : Affiche l'état de l'arbre de travail et de l'index. Il montre les modifications qui ont été ajoutées à l'index (staged), celles qui ne le sont pas (unstaged), et les fichiers non suivis.

git add . : Ajoute toutes les modifications (nouvelles modifications et fichiers supprimés) de l'arbre de travail à l'index (staged) pour le prochain commit.

git add journal.md TODO.md : Ajoute les fichiers `journal.md` et `TODO.md` à l'index (staged) pour le prochain commit.

git commit -m "Create .md files" : Crée un commit avec un message descriptif "Create .md files" pour les modifications qui ont été ajoutées à l'index.

git push : Envoie les commits locaux vers le dépôt distant, rendant les changements disponibles aux autres collaborateurs.

nano journal.md : Ouvre le fichier `journal.md` dans l'éditeur de texte `nano` pour l'éditer.

git status : Affiche à nouveau l'état de l'arbre de travail et de l'index, après avoir modifié des fichiers.

git log --graph --all : Affiche l'historique des commits avec un graphe ASCII montrant les branches et les commits.

cd Documents/dev/ci_cd_gourgouillon_bilger : Change le répertoire de travail actuel pour `Documents/dev/ci_cd_gourgouillon_bilger`.

git blame journal.md : Affiche les informations sur l'auteur de chaque ligne dans `journal.md`. Chaque ligne est précédée par l'identifiant du commit, l'auteur, et la date du dernier changement.

cd Documents/dev/ci_cd_gourgouillon_bilger : Commande répétée, change à nouveau le répertoire de travail pour `Documents/dev/ci_cd_gourgouillon_bilger`.

git blame journal.md : Commande répétée, affiche à nouveau les informations sur l'auteur de chaque ligne dans `journal.md`.

touch journal.md : Crée un fichier vide nommé `journal.md` s'il n'existe pas, ou met à jour la date de modification s'il existe.

touch TODO.md : Crée un fichier vide nommé `TODO.md` s'il n'existe pas, ou met à jour la date de modification s'il existe.

git status : Affiche à nouveau l'état de l'arbre de travail et de l'index après avoir créé de nouveaux fichiers.

git add . : Ajoute toutes les modifications de l'arbre de travail à l'index (staged) pour le prochain commit.

git commit -m "Create .md files" : Crée un commit avec un message descriptif "Create .md files" pour les modifications ajoutées à l'index.

git push : Envoie les commits locaux vers le dépôt distant.

git add journal.md : Ajoute le fichier `journal.md` à l'index (staged) pour le prochain commit.

git commit -m "Update journal.md" : Crée un commit avec un message descriptif "Update journal.md" pour les modifications apportées à `journal.md`.

git push : Envoie les commits locaux vers le dépôt distant.

git status : Affiche à nouveau l'état de l'arbre de travail et de l'index.

git checkout -b first-branch : Crée une nouvelle branche nommée `first-branch` et bascule dessus.

git add *.md : Ajoute tous les fichiers avec l'extension `.md` à l'index (staged) pour le prochain commit.

git commit -m "Update journal.md" : Crée un commit avec un message descriptif "Update journal.md" pour les modifications apportées aux fichiers `.md`.

git push : Envoie les commits locaux vers le dépôt distant.

git push --set-upstream origin first-branch : Envoie la branche `first-branch` vers le dépôt distant et définit le dépôt distant comme upstream pour cette branche.

git add journal.md : Ajoute le fichier `journal.md` à l'index (staged) pour le prochain commit.

git commit -m "Update journal.md 2" : Crée un commit avec un message descriptif "Update journal.md 2" pour les modifications apportées à `journal.md`.

git push : Envoie les commits locaux vers le dépôt distant.

git status : Affiche à nouveau l'état de l'arbre de travail et de l'index.

git checkout main : Bascule sur la branche principale `main`.

git status : Affiche à nouveau l'état de l'arbre de travail et de l'index.

git log --graph --all : Affiche à nouveau l'historique des commits avec un graphe ASCII.

git cherry-pick 0967fe38a8b6cf644c3362e28a76e7ee5a5d959c : Applique les modifications introduites par le commit spécifié sur la branche courante.

git push : Envoie les commits locaux vers le dépôt distant.

git status : Affiche à nouveau l'état de l'arbre de travail et de l'index.

git log --graph --all : Affiche à nouveau l'historique des commits avec un graphe ASCII.

git blame journal.md : Affiche à nouveau les informations sur l'auteur de chaque ligne dans `journal.md`.

git add journal.md : Ajoute le fichier `journal.md` à l'index (staged) pour le prochain commit.

git commit -m "Explication git blame journal.md" : Crée un commit avec un message descriptif "Explication git blame journal.md" pour les modifications apportées à `journal.md`.

git push : Envoie les commits locaux vers le dépôt distant.