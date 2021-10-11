# lister les commits 
git log : : les commits réalisés 
git log-1 : info du renier commit

git log - --stat 
----> voir le commit qui a fait quoi etc...

## status : 
git status pour avoir un statut 

# git diff 
pour avoit le detail de ce qu'a été

## retrouver un commit : 
git log -s "chaine à rechercher"

## resert : 
git reset --hard HEAD 
git reset HEAD

## recuperer ficher 
aprés avoir supprimer un fichier exemple 
+ on fait git log .
+ je prends 8 lettre de mon commit .
+ git reset --hard(shift insert code 7 lettres) ......

## git fetch 
+ se mettre à jour avec ce qu'on a sur le distant  . 

## annuler le suivi d'un fichier  
git rm --cached * nom_fichier*
