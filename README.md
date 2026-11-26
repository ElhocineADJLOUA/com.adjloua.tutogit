# Documentation du tuto Github avec Git
## Initialisation du dépôt 

```bash
git init 
git remote add origin SSH_REPOT (Ex : git@github.com:ElhocineADJLOUA/com.adjloua.tutogit.git)
```

## Rédiger un commit (bonne pratique)
```
Titre du commit 

Description de notre commit avec des informations sur l'evolution du projet
```


## Envoyer un commit sur le dépot distant

```bash
git add.
git commit -m "Titre du commit"
git push origin main

```

## Création d'une branch 

```bash
git branch -b NOM_BRANCH
```

Pour les bonnes pratique, on va integrer la notion de revue de code. pour cela , on va créer une branche, faire des modifications, les envoyer sur le dépot distant, puis créer une pull request pour demander une revue de code