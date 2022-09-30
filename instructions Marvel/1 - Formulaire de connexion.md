
## I) Formulaire de Connexion

La première étape consiste a créer une page de connexion, dans lequel on aura un formulaire qui permettra aux utilisateur de se connecter.

Vous devrez créer plusieurs composants pour cette page, un composant `logo`, qui affichera le logo Marvel, un composant `loginForm` (Que vous pouvez découperez en plusieurs composant), qui gérera le formulaire de connexion.

Le formulaire doit être un formulaire controlé, c’est a dire que les elements du formulaire (un champ `username` et `password`) doivent être géré par la state du composant (Comme sur la TodoList).

Afficher une erreur si le ```username``` fait moins de 3 characteres, ainsi que si le ```password``` fait moins de 8 characteres.

Le formulaire doit aller récupérer un token de connection à cette adresse:

https://easy-login-api.herokuapp.com/users/login

Il s’agit d’une requête ```POST``` qui nécessite un champ ```username``` et un champ ```password```

Pas besoin de créer un utilisateur, cette API renvoi un token de connection lorsque les deux champs ci dessus sont envoyés.

Il faudra ensuite stocker le token dans le localStorage, puis redirigé l’utilisateur vers la page characters.

## Objectif de l'exercice
* Comprendre et mettre en place un formulaire controlé
* Verifier les infos et faire un retour à l'utilisateur en cas d'erreur avant d'envoyer le formulaire
* Stocker le token et rediriger l'utilisateur

## Quelles ressources utilisé ?
* useState pour gérer le contenu du formulaire (Voir Todolist).
* Voir AsyncStorage pour manipuler le token

## A savoir
* le token est stocké dans le header de la réponse