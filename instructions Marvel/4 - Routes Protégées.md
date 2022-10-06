 ## IV ) Routes protégées 
 
 Vous devrez faire en sorte que les utilisateurs sans token de connexion soit redirigés vers l'ecran login et que les utilisateurs ayant un token ne puissent pas aller sur l'ecran Login (qu'ils soient redirigés vers l'écran characters).

## Objectif de l'exercice
* Sécuriser son application.

## Quelles ressources utiliser ?
* Voir [Authentication flows](https://reactnavigation.org/docs/auth-flow) sur React Navigation


## BONUS

Vérifier si le token est valide en envoyant une requête à l'API suivante (methode ```GET```):
https://easy-login-api.herokuapp.com/protected
Pour vérification, si le token est incorrect, supprimez le token de l'application et redirigez l'utilisateur vers la page `login`.
