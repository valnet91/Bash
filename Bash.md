# Langage: BASH

| Langage  | category |
| ------------- | ------------- |
| Bash  | Débutant  |

***


![Langage: BASH](Gnu-bash-logo.svg.png)

### 📢 Commande : PWD
    -Permet de vérifier, de connaitre dans quel répertoire nous sommes.
```bash
$ pwd puis Entrée
```
#
### 📢 Commande : ls
    -Liste les fichiers et dossiers présent dans le répertoire.
```bash
$ ls puis Entrée
```
#
### 📢 Commande : ls -la
    -Liste les fichiers, les dossiers et les fichiers et dossiers cachés (dont le nom commence par un point et les attibuts des fichiers et dossiers `chmod`) présent dans le répertoire.
```bash
$ ls -la puis Entrée
```
#
### 📢 Commande : clear
    -Permet de nettoyer son écran.
```sh
$ clear puis Entrée
```
#
### 📢 Commande : history
    -Permet de lister les x (500) dernières commandes que vous avez saisies.
```shell
$ history puis Entrée
```
#
### 📢 Commande : cat nom_de_fichier.txt
    -Permet de voir/lire le contenu du fichier.
```bash
$ cat nom_de_fichier.txt puis Entrée
```



#
### 📢 Commande raccourci : grep "test" le terminal est bloqué !?
    -Permet de revenir à un terminal propre.
```bash
$ Ctrl + Maj + D fermera votre terminal en cours et en ouvrira un autre. Faites un  `pwd` pour savoir dans quel répertoire vous êtes.
```

#
### 📢 Commande : ls | grep nom_de_fichier.txt
    -Listera le fichier README.md si il est présent dans le répertoire courant.
```bash
$ ls | grep nom_de_fichier.txt puis Entrée
```

#
### 📢 Commande : ls | grep .txt
    -Listera les fichiers avec l'extension txt du répertoire courant.
```bash
$ ls | grep .txt puis Entrée
```

#
### 📢 Commande : echo votre_texte >> nom_de_fichier.txt
    -Création du fichier nom_de_fichier.txt avec le texte votre_texte dans le répertoire courant.
```bash
$ echo texte1 >> test.txt puis Entrée
$ echo Ajout de texte2  à mon texte1 >> test.txt puis Entrée
`>>` le double chevron fermant permet de faire un ajout à la suite du texte1 déjà existant -> cf 'append'
```

<!-- 
; ex: cat README.md
; 📢 cat nom_de_fichier
; ex: cat README.md
; @valnet91 :+1: This PR looks great - it's ready to merge! :shipit:
-->
