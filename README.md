# Git Training

Bienvenue dans ce repository de formation Git ! Ce projet vous permet de vous entraîner aux principales commandes de Git.

## Objectifs

Ce repository est conçu pour vous aider à maîtriser les commandes Git essentielles à travers la pratique.

## Commandes Git de base

### Configuration initiale
```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre.email@example.com"
```

### Commandes essentielles

#### Créer et cloner un repository
```bash
git init                    # Initialiser un nouveau repository
git clone <url>            # Cloner un repository existant
```

#### Travailler avec les fichiers
```bash
git status                 # Voir l'état des fichiers
git add <fichier>         # Ajouter un fichier à l'index
git add .                 # Ajouter tous les fichiers modifiés
git commit -m "message"   # Créer un commit
git rm <fichier>          # Supprimer un fichier
git mv <ancien> <nouveau> # Renommer un fichier
```

#### Synchronisation avec le remote
```bash
git pull                  # Récupérer et fusionner les changements
git push                  # Envoyer les commits vers le remote
git fetch                 # Récupérer les changements sans fusionner
```

#### Branches
```bash
git branch                # Lister les branches
git branch <nom>          # Créer une nouvelle branche
git checkout <branche>    # Changer de branche
git checkout -b <nom>     # Créer et basculer sur une nouvelle branche
git merge <branche>       # Fusionner une branche
git branch -d <branche>   # Supprimer une branche
```

#### Historique
```bash
git log                   # Voir l'historique des commits
git log --oneline         # Historique condensé
git diff                  # Voir les différences
git show <commit>         # Afficher un commit spécifique
```

#### Annuler des changements
```bash
git reset <fichier>       # Retirer un fichier de l'index
git checkout -- <fichier> # Annuler les modifications d'un fichier
git revert <commit>       # Annuler un commit en créant un nouveau commit
git reset --hard <commit> # Réinitialiser à un commit spécifique (attention !)
```

## Structure du projet

- `README.md` - Ce fichier de documentation
- `index.html` - Page d'accueil du projet

## Comment utiliser ce repository

1. Clonez ce repository
2. Expérimentez avec les commandes Git listées ci-dessus
3. Créez des branches, faites des commits, et pratiquez les différentes opérations
4. N'hésitez pas à faire des erreurs, c'est en pratiquant qu'on apprend !

## Ressources supplémentaires

- [Documentation officielle Git](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/fr/v2)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## Contribution

Ce repository est à but éducatif. N'hésitez pas à proposer des améliorations !