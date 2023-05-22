# INTRO

Git et github permettent de créeer des versions d'un projet, Cela permet de revenir a une version anterieur du projet si besoin. L'avantage de github est qu'il permet de travailler a plusieurs dur meme projet , de créeer des branches pour travailler sur une fonctionnalité sans impacter le projet principal.

# GIT 

Git est un VCS (Version Contriol Systeme) qui permet de créer des versions d'un projet. Avec git , les versions de notreprojet sont stockées dans un dossier cacgé nommé .Git . Ce dossier contient l'historique des modifs apporté a notre projet .


# GITHUB

Github est un service en ligne qui permet de 'heberger des projet utillisant git . donc grace a github on peut héberger nos projet en ligne afin de pouvoir y acceder depuis nimporte quel ordinateur.

## 2. Les commandes de bases

### Depot local

Pour initialiser git sur un prjoet local , il faut ouvrir le projet dans le termianl en faisant : " cd chemin/vers/le/projet" qui va pointer dans le dossier du projet.

ensuite il faut faire git init pour initialiser git sur le projet

par defaut git ne va pas prendre en compte tous les fichiers du projet.

Pour ajouter un fichier au duivie de git, il faut faire  git add nomdufichier.

Pour ajouter tout les fichiers du projet, il faut faire git add. ou git add -A

Pour verifier l'état du projet , il faut faire git status qui va afficher 


# Exo
Cree un fichier about.html et faites en sorte que ce fichier et le fichier contact.html sois pris en compte par git 

##


Pour créer un commit, il faut faire git commit -m "message du commit" Soyez le plus precis possible dans le messge du commit afin de pouvoir retrouver facilement le commit que vous cherchez

aVANT DE FAIRE UN COMMIT ( une version), il faut configurer 

Pour voir l'hisoriquedes commit il faut faire git log

Pour modifier le message du dernier commit il faut faire 'git commit --amend cela va ouvrir l'editeur vim et ajouter les modifications il faut appuyer sur la touche 'i' pour passer en mode insertion, faire les modifications puis appuyer sur la touche echap et taper :wq! pour enregistrer et quiter.

VIM

':' permet d'entrer une commande
'q' permet de quitter sans enregistrer 
'q!' permet de forcer la fermeture sans enregistrer 
'w' permet d'enregistrer 
