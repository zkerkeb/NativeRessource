# Aide Mémoire Réact Native 

## Lancer son projet
---


### Android

```npx react-native run-android```

### IOS

### Android

```npx react-native run-ios```


### Lancer le bundler


```npx react-native start```

> Attention: les commandes au dessus lancent le bundler automatiquement normalement, si ce n'est pas le cas lancer le avant de faire les commande au dessus.


---
## Lancer la console de dev sur le simulateur

### Android

```Ctrl + m```

### Ios

```Ctrl + d```

> Cliquez ensuite sur Debug et une page internet s'ouvrira, cliquez sur inspectez puis sur console pour voir vos log.
---
## FAQ

### Mon application ne reconnais pas le paquet NPM que je viens d'installer 

> Couper le bundler (Le terminal avec le carré bleu), et le relancer avec la commande suivante:

`npx react-native start --reset-cache`

> --reset-cache permet de nettoyer le cache du bundle et donc d'éviter d'avoir une version obsolète de votre app.

### Nettoyer l'application android

> Faire la commande suivante

```cd android && ./gradlew clean```

> Revenir ensuite dans le dossier de votre app et relancez l'application, redémarrez également le bundler



