# Création App Marvel / Mise en place du Routeur


Pour prendre en main React Native nous allons créer une petite application qui présentera nos supers héros préférés.

Le but de l’exercice est de pratiquer React Native et d’être à l’aise avec la creation de composant, ainsi que la manipulation de donnée retourné par une API.

Cet exercice a pour but de vous faire voir les notions suivantes:

1. Créer un formulaire controlé (les champs sont relié a la state)
2. Validateur de formulaires (Vérifier les données entré dans le formulaire)
3. Créer une application multi-pages avec React-Router
4. Créer un système de Routes protégés (partie accessible uniquement aux personnes connecté)
5. Récupérer les paramètres d’une routes (permet de faire un appel API avec l’id d’un personnage par exemple)
6. Consommé une API, garder certaines informations disponible en hors ligne.
7. Mise en place d’un système de thème.

Nous avons travaillé jusqu’a présent sur une single page App, notre app ne gérer pas le multi-page. 

Nous utiliserons ```React Navigation``` ([voir doc](https://reactnavigation.org/)) pour cela, avant de commencer l’exercice, créer un routeur avec deux pages,  une page ```login``` et une page ```characters```. Vous afficherez ce que vous voudrez sur ces pages dans un premier temps, Créer un bouton qui vous envoie de la page ```login``` a la page `characters` et vice versa

Les liens de votre routeur devront être « / » pour la page ```login``` et « /characters » pour la page ```characters```

## Objectif de l'exercice
* Installer React Navigation
* Mettre en place une App multi-page
* Naviguer entre les pages créés

## Quelles ressources utilisé ?
* Pour le multi-page, le ```Stack Navigator``` de React Navigation
* Pour la navigation entre plusieurs solutions sont dans la [doc](https://reactnavigation.org/)








