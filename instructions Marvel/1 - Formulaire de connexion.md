
## I) Formulaire de Connexion

La première étape consiste à créer une page de connexion dans laquelle on aura un formulaire qui permettra aux utilisateurs de se connecter.

Vous devrez créer plusieurs composants pour cette page: un composant `logo` qui affichera le logo Marvel, un composant `loginForm` (que vous pouvez découper en plusieurs composants) qui gérera le formulaire de connexion.

Le formulaire doit être un formulaire controlé, c’est à dire que les éléments du formulaire (un champ `username` et `password`) doivent être gérés par la state du composant (comme sur la TodoList).

Afficher une erreur si le ```username``` fait moins de 3 caractères, ainsi que si le ```password``` fait moins de 8 caractères.

Le formulaire doit aller récupérer un token de connexion à cette adresse:

https://easy-login-api.herokuapp.com/users/login

Il s’agit d’une requête ```POST``` qui nécessite un champ ```username``` et un champ ```password```.

Pas besoin de créer un utilisateur, cette API renvoie un token de connexion lorsque les deux champs ci-dessus sont envoyés.

Il faudra ensuite stocker le token dans le localStorage, puis rediriger l’utilisateur vers la page characters.

## Objectif de l'exercice
* Comprendre et mettre en place un formulaire controlé.
* Verifier les infos et faire un retour à l'utilisateur en cas d'erreur avant d'envoyer le formulaire.
* Stocker le token et rediriger l'utilisateur.

## Quelles ressources utiliser ?
* useState pour gérer le contenu du formulaire (voir Todolist).
* Voir AsyncStorage pour manipuler le token.

## À savoir
* Le token est stocké dans le header de la réponse.
