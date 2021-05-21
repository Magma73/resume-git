# Index collaboratif des commandes `git`



## Revenir à la liste des commandes

Pour revenir à la liste complète des commandes, [cliquez ici](index.html)



## Commande `git commit`


### Description

La commande `git commit` permet de valider les modifications qui sont dans la zone de staging.

Un commit est tout simplement un enregistrement de votre travail à un instant T sur la branche courante où vous êtes. 


### Exemples

```
$ git commit

```

Cette action lance votre éditeur choisi.

L’éditeur affiche le texte suivant :

```
# Veuillez saisir le message de validation pour vos modifications. Les lignes
# commençant par '#' seront ignorées, et un message vide abandonne la validation.
# Sur la branche master
# Votre branche est à jour avec 'origin/master'.
#
# Modifications qui seront validées :
#       nouveau fichier : LISEZMOI
#       modifié :         CONTRIBUTING.md
#

```
Quand vous quittez l’éditeur (après avoir sauvegardé le message), Git crée votre commit avec le message de validation.


Il est également possible d'utiliser l'option -m pour spécifier directement le message de validation en ligne.

```
$ git commit -m "Votre message"

```



