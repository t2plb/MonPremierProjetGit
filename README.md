<div style="text-align:left;">Titouan Bonnet Plomb</div>
<br>
<h2><b><div style="text-align:center">Rendu TP</div></b></h2>

### Partie 1
1.	Initialisation d’un repertoire
    1.	La commande git init permet d’initialiser un repository git.
    2.	Git add permet d’ajouter les fichiers récemment ajouter ou bien récemment modifié au commit, et git commit permet de mettre à jour le repository local
    3.	Parce que ce sont les messages qui vont se retrouver sur le repository en ligne
2.	Historique et modifications
    1.	Git commit main.c
    2.	Chaque ligne représente un commit effectuer sur le repository local
    3.	Il sert à regarder les différences entre le fichier local et le fichier stocké par le repository
3.	Utilisation de. gitignore
    1.	Pour ne pas envoyer de fichiers qui peuvent être sensible ou par exemple pour éviter les conflits lors des merges.
### Partie 2
1.	Création d’un dépôt GitHub
    1.	Un repo public est un repo accessible à tout le monde, un repo privé est un repo accessible à des utilisateurs sélectionné
2.	Lier le dépôt local à GitHub
    1.	Elle permet de rajouter un dépôt distant qui recevra le dépôt local
    2.	Est un raccourci de git push –set-upstream
### Partie 3
1.	Créer et gérer des branches
    1.	Pour éviter « d’écraser » le travail des autres et d’eviter les conflits si jamais chacun travail sur un bout de code particulier
    2.	Git branch
2.	Pull Request (PR)
    1.	Pour historiser les pull request et savoir qui a merger la branch dans la branch main et pourquoi
### Partie 4
1.	GitHub Flow
    1.	Github flow est préférable pour les petits projets
2.	Git Flow
    1.	La branche hotfix contient les corrections de bugs effectué
### Partie 5
1.	Cloner un projet
    1.	Git clone permet de récupérer l’intégralité d’un repo (branches comprises) et le git pull permet de récupérer les dernières mise à jour de branche d’un repo déjà cloné
### Partie 6
1.	Rebase
    1.	Merge permet de mettre à jour la branch main avec les commits et rebase met jour à jour sans l’historique de commit
2.	Cherry-pick
    1.	Pour se rebaser sur un commit plus ancien
### Partie 7
1.	Ajouter un submodule
    1.	Pour éviter à avoir un trop gros code à maintenir. Le submodule permet de séparer son code en différent repo plus simple à maintenir
2.	Initialiser et mettre à jour les submodules
    1.	git submodule update –remote
