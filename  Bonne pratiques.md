# Bonne Pratique

## Mettre en place une structure et une  nomenclature
---
![Nomenclature](./assets/nomenclature.png)

### Structure

>React Native nous donne zéro structure de base, il faut donc créer la notre nous même.

* Créer un dossier ```src``` qui contiendra tout ce qui est necessaire au bon fonctionnement de votre App.

* Créer un dossier ```components``` qui contiendra vos composant
    > Notez que chaque composant est dans un dossier, ce n'est pas anodin, ça nous permet de créer proprement des composants (on pourra y mettre le style, les tests, etc...) 

* Créer un dossier ```config``` qui contiendra vos fichier de configuration (initialisation des Routes, Theme, internalisation, etc...)

* Créer un dossier ```screens``` qui contiendra vos pages, les pages sont des composant comme les autres, la seule difference que l'on fait ici est logique et est faite pour avoir une structure prore, les pages contiendront d'autre composant qui formeront la page

* Créer un dossier ```utils``` qui contiendra vos petites fonctions qui sont utilisé un peu partout sur votre app.

### Nomenclature

La règle est simple, choisissez une règle de nommage et tenez vous-y dans toute votre app (Camel Case dans mon cas)


> Je ne vous demande pas forcement de suivre bêtement les instructions presentés ici mais vous conseille fortement d'avoir une structure logique et propre