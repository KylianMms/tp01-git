# TP01 — Découverte de Git

Dépôt réalisé par Kylian Manas--Montels, 1CIEL-IR.

Ce dépôt contient mon compte rendu du T01.

# Partie 1

## Question 1
https://github.com/KylianMms

# PARTIE 2
## Question 2 
1. 
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
user.name=KylianMms
user.mail=https://github.com/KylianMms
init.defaultbranch=main
core.editor=nano'''

2. 
L'option global signifie à Git d'appliquer l'action à l'utilisateur connecté sur la machine. Ils sont enregistrés dans ~/.gitconfig

# Partie 3
## Question 3.1
1. 
fatal: ni ceci ni aucun de ses répertoires parents (jusqu'au point de montage /) n'est un dépôt git
Arrêt à la limite du système de fichiers (GIT_DISCOVERY_ACROSS_FILESYSTEM n'est pas défini).
C'est car le dossier n'est pas un dépot.

## Question 3.2
1.  
git init a crée le dossier .git qui était un dossier caché.

2. 
Sur la branche main

Aucun commit

rien à valider (créez/copiez des fichiers et utilisez "git add" pour les suivre)

## Question 3.3
1.  
IL est rangé dans le répoertoire de travail.

## Question 3.4
1.  
README.md est maintenant enregistré.

## Question 3.5
1.  
commit c50e6c0d70a61548e625605b44a44d1dd0faac53 (HEAD -> main)
Author: KylianMms <kmanasmontels@d116-07.lab.rascol-info.org>
Date:   Thu Oct 1 11:18:29 2026 +0200

    Création du README

2. 
Le hash est c50e6c0 .
Son auteur est KyliaMms .
La date est Thu Oct 1 11:18:29 2026 .
Le message est Création du README .

3.  
Le hash contient 7 caractères.
IL est écrit en base de 8. 
Il re présente 4 bits.

## Question 3.7
1. 
Le git status décrit README comme étant modifié.

2.  
Le + signifie que la ligne a été ajoutée.
Et il montre avec un - les lignes supprimées. 
Il montre donc les modifications faites.

## Question 3.8 


