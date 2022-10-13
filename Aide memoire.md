# Aide Mémoire Réact Native 

## Lancer son projet.
---


### Android

```npx react-native run-android```

### IOS


```npx react-native run-ios```


### Lancer le bundler.


```npx react-native start```

> Attention: les commandes au-dessus lancent le bundler automatiquement normalement. Si ce n'est pas le cas, lancez-le avant de faire les commandes au-dessus.


---

## Lancer la console de dev sur le simulateur.

### Android

```Ctrl + m```

### Ios

```Ctrl + d```

> Cliquez ensuite sur « Debug » et une page internet s'ouvrira. Cliquez sur « inspectez » puis sur « console » pour voir vos log.
---
## Installer un paquet.

avec npm :

```npm install [Nom du paquet] --save```

>Le --save permet d'ajouter le paquet à votre package.json, et donc de pouvoir le réinstaller si vous git cloner votre app sur une autre machine. 

avec yarn :

```yarn add [Nom du paquet]```

---
## FAQ

### Mon application ne reconnait pas le paquet NPM que je viens d'installer.

> Coupez le bundler (le terminal avec le carré bleu), et le relancer avec la commande suivante:

`npx react-native start --reset-cache`

> --reset-cache permet de nettoyer le cache du bundle et donc d'éviter d'avoir une version obsolète de votre app.
---
---
### Nettoyer le bundle de l'application android.

> Faire la commande suivante:

```cd android && ./gradlew clean```

> Revenir ensuite dans le dossier de votre app et relancez l'application. Redémarrez également le bundler.
---
---

### Faire un nettoyage complet de ses applications React Native [MACOS].

Exécutez les commandes suivantes dans l'ordre:

1.```watchman watch-del-all```

2.```rm -rf yarn.lock package-lock.json node_modules```

3.```rm -rf android/app/build```

4.```rm -rf ios/Pods ios/Podfile.lock``` 

5.```rm -rf ~/Library/Developer/Xcode/DerivedData```

6.```npm install && cd ios && pod update && cd ..```

7.```npm start --reset-cache```

Relancez ensuite l'application.

---
---

### Faire un nettoyage complet de son application React Native [Windows].

Exécutez les commandes suivantes dans l'ordre:

1.```watchman watch-del-all```

2.```rm -r yarn.lock package-lock.json node_modules```

3.```rm -r android/app/build```

4.```npm install```

5.```npm start --reset-cache```

Relancez ensuite l'application.
