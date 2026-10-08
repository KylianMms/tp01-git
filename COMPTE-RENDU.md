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
Il montre donc les modifications faite.

## Question 3.8 
1. 
83c63f2 (HEAD -> main) ...
a3a5c95 Création de l'aide-mémoire Git
d55abef Ajout de l'année scolaire dans le README
5ef9d14 Ajout du compte rendu (questions 0 à 3.5)
c79f1bb Ajout du compte rendu (questions 0 à 3.5)
c50e6c0 Création du README

2.  
Faire plusieurs commits logiques plutôt qu'un unique git add . suivi d'un gros  permet d'assurer les modifications et de faciliter la maintenance du code.

# Partie 4
## Question 4.1 
commit 83c63f276c329735b00a874c35cbd799f2b32970 (HEAD -> main)
Author: KylianMms <kmanasmontels@d116-06.lab.rascol-info.org>
Date:   Thu Oct 8 09:50:25 2026 +0200

    ...

diff --git a/COMPTE-RENDU.md b/COMPTE-RENDU.md
index 0a1c033..9c9d307 100755
--- a/COMPTE-RENDU.md
+++ b/COMPTE-RENDU.md
@@ -69,7 +69,15 @@ Le hash contient 7 caractères.

## Question 4.2 
Il a récupéré dans l'historique l'ancienne sauvegrade du README. 
Si on avait jamais commité on aurait pas pu le récupérer car il n'aurait pas été dans l'historique.

## Question 4.3 
Il se trouve dans le répertoire de travail.
Le fichier n'a pas été supprimé du disque.

## Question 4.4 
1.  
Les fichiers touch brouillon.txt erreurs.log debug.log ont disparus.
Ca ignore les fichiers en les supprimant du dépot.

2.  
Il y a le .gitignore et il faut le commmiter.

## Question 4.5 
Problème de commande je ne sais pas.

# Partie 5

## Question 5.2
1.  
Les fichiers id_ed25519 et id_ed25519.pub ont été créer. Le premier est la clé privée et le deuxieme la clée privée.

2.  
-rwx et -rwx

## Question 5.4
1.  
The authenticity of host 'github.com (140.82.121.4)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi KylianMms! You've successfully authenticated, but GitHub does not provide shell access.

2.  
Car la clé privée c'est le mdp.

# Partie 6

## Question 6.3
1.  
origin  git@github.com:KylianMms/tp01-git.git (fetch)
origin  git@github.com:KylianMms/tp01-git.git (push)

**Énumération** des objets: 17, fait.
Décompte des objets: 100% (17/17), fait.
Compression par delta en utilisant jusqu'à 12 fils d'exécution
Compression des objets: 100% (15/15), fait.
Écriture des objets: 100% (17/17), 3.03 Kio | 1.51 Mio/s, fait.
Total 17 (delta 3), réutilisés 0 (delta 0), réutilisés du pack 0
remote: Resolving deltas: 100% (3/3), done.
To github.com:KylianMms/tp01-git.git
 * [new branch]      main -> main
la branche 'main' est paramétrée pour suivre 'origin/main'.

## Question 6.4 a
Mon dépot local ne contient pas la modification. 
git commit ne me prévient âs d'un commit récent.

## Question 6.4 b
J'ai récupéré le dernier commit de github et l'auteur est  moi même.

