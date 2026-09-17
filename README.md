# Premier Projet

Je fais un travailler de test et de fusionner de deux branches

Je vais en profiter pour dire ce que j'ai appris aujourd'hui

# Git : 
	est uu outil de gestion de version installer sur un pc, il permet de suivre les modifications de
	ton projet les modifications et ajout, fait par qui, quand et pourquoi. Il permet aussi de revenir 
	a une ancienne version et de travailler sur plusieurs version du projet sans casser.

# GitHub :
	 est une plateforme en ligne qui permet notamment d'héberger des dépôts Git et de collaborer
	avec d'autre développeurs.

# Dépôt :
	Un dépôt ou Repository / repo est un androt ou Git conserve un projet son historique.
	Un dépôt se creer par la commande suivant pour initialiser Git, dans le dossier du projet
```bash
git init
```

# Commit: 
	Un commit est une sorte de point de sauvegarde des historique du projet
	Avant de un commit on verifie le status les modification et ajout depuis la dernier commit
	puis on ajout ces modifications avec add au commit a prochain puis on commit
```bash
git status
git add .
git commit -m "description de la modification ou ajout"
```


# Branche:
	Une branche est une version parallèle du devéllopement du projet.
```bash
git checkout -b nom_branche
ou
git switch -c nom_branche
```

# Merge :
	Le merge signifie de fusionner les modificaions d'une branche a une autre.
``` bash
git merge nom_branch
```

# Pull Request :
	La Pull Resquet est une demande de fusion d'une branche vers une autre, généralement sur GitHub

# Commendes essentielles 

# Clone : 
	clone sert a télécharger un dépôt distant sur son ordinateur
```bash 
git clone URL
```

# satus:	
	status permet de voir les l'etat actuel du projet
```bash
git status 
```

# add: 
	add prepare les modifications pour le nouveau commit
``` bash
git add .
```

# push:
	push envoyer les commits sur GitHub
```bash
git push
```

