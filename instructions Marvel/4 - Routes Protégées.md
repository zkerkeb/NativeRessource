 ## IV ) Routes protégées 
 
 Vous devrez faire en sorte que les utilisateurs sans token de connexion soit redirigé vers l'ecran login, Et que les utilisateurs ayant un token ne puissent pas aller sur l'ecran Login, qu'il soient redirigé vers l'ecran characters.

## Objectif de l'exercice
* Sécurisez son application

## Quelles ressources utilisé ?
* Voir [Authentication flows](https://reactnavigation.org/docs/auth-flow) sur React Navigation


## BONUS

Verifier si le token est valide en envoyant une requête a l'API suivante (methode ```GET```) https://easy-login-api.herokuapp.com/protected pour verification, si le token est incorrect, supprimer le token de l'application et rediriger l'utilisateur vers la page `login`.
