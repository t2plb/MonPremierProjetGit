Titouan Bonnet Plomb
Rendu TP

Partie 1
1.	Initialisation d’un repertoire
a.	La commande git init permet d’initialiser un repository git.
b.	Git add permet d’ajouter les fichiers récemment ajouter ou bien récemment modifié au commit, et git commit permet de mettre à jour le repository local
c.	Parce que ce sont les messages qui vont se retrouver sur le repository en ligne
2.	Historique et modifications
a.	Git commit main.c
b.	Chaque ligne représente un commit effectuer sur le repository local
c.	Il sert à regarder les différences entre le fichier local et le fichier stocké par le repository
3.	Utilisation de. gitignore
a.	Pour ne pas envoyer de fichiers qui peuvent être sensible ou par exemple pour éviter les conflits lors des merges.
Partie 2
1.	Création d’un dépôt GitHub
a.	Un repo public est un repo accessible à tout le monde, un repo privé est un repo accessible à des utilisateurs sélectionné
2.	Lier le dépôt local à GitHub
a.	Elle permet de rajouter un dépôt distant qui recevra le dépôt local
b.	Est un raccourci de git push –set-upstream
Partie 3
1.	Créer et gérer des branches
a.	Pour éviter « d’écraser » le travail des autres et d’eviter les conflits si jamais chacun travail sur un bout de code particulier
b.	Git branch
2.	Pull Request (PR)
a.	Pour historiser les pull request et savoir qui a merger la branch dans la branch main et pourquoi
Partie 4
1.	GitHub Flow
a.	Github flow est préférable pour les petits projets
2.	Git Flow
a.	La branche hotfix contient les corrections de bugs effectué
Partie 5
1.	Cloner un projet
a.	Git clone permet de récupérer l’intégralité d’un repo (branches comprises) et le git pull permet de récupérer les dernières mise à jour de branche d’un repo déjà cloné
Partie 6
1.	Rebase
a.	Merge permet de mettre à jour la branch main avec les commits et rebase met jour à jour sans l’historique de commit
2.	Cherry-pick
a.	Pour se rebaser sur un commit plus ancien
Partie 7
1.	Ajouter un submodule
a.	Pour éviter à avoir un trop gros code à maintenir. Le submodule permet de séparer son code en différent repo plus simple à maintenir
2.	Initialiser et mettre à jour les submodules
a.	git submodule update –remote
