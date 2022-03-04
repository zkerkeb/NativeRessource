## II ) Page characters

Vous consommerez l’API Marvel - [Creer un compte ici ](https://developer.marvel.com) - pour afficher une liste des personnages Marvel, vous devez gérer la pagination (faire des requêtes supplémentaire pour avoir la suite de la liste).

À la selection d’un personnage, on est redirigé vers la page `details`, qui donnera plus d’informations sur le personnage en questions.

## Objectif de l'exercice
* Consommation d'une API
* Creation d'un scroll infini
* Navigation vers une page en envoyant des paramètres

## Quelles ressources utilisé ?
* axios pour le call API
* FlatList pour l'affichage de la liste et le scroll infini

## A savoir
* N'envoyez pas les informations du personnage en paramètres dans la page détails, uniquement l'id, pour vous permettre de le récuperer et de requeter l'API avec l'id pour plus d'informations.