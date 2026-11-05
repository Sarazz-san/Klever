# Klever

Klever est un projet d’application mobile de culture générale et de stratégie, développé avec React Native pour iOS et Android. Le jeu mêle connaissances et tactique autour de deux mécanismes : **l’Échange**, où les joueurs donnent à tour de rôle des réponses valides, et **l’Enchère**, où ils misent sur le nombre de réponses qu’ils pensent pouvoir fournir.

Le concept prévoit trois formats de jeu — **Tournoi**, **Face-to-face** et **All-team** — ainsi que des packs de questions personnalisables. Les règles et les fonctionnalités envisagées sont décrites dans le dossier du projet.

> **État du projet :** le dépôt contient actuellement la base d’une application React Native. Les modes de jeu et les fonctionnalités décrits dans la documentation constituent la vision du projet et ne sont pas nécessairement déjà implémentés dans l’application.

## Documentation

- [Cahier des charges](docs/cahier_des_charges.md) — fonctionnalités et exigences prévues.
- [Documentation du jeu](docs/le_jeu_documentation.md) — règles et formats de jeu.
- [Design](docs/design.md) — éléments de conception.

## Prérequis

- Node.js **22.11.0 ou supérieur** (voir `engines` dans `package.json`).
- L’environnement de développement React Native configuré pour [Android et/ou iOS](https://reactnative.dev/docs/set-up-your-environment).
- Pour iOS : macOS, Xcode et CocoaPods.

## Installation

Clonez le dépôt puis installez les dépendances JavaScript :

```sh
git clone https://github.com/Sarazz-san/Klever.git
cd Klever
npm install
```

Pour iOS, installez également les dépendances CocoaPods :

```sh
cd ios
bundle install
bundle exec pod install
cd ..
```

## Lancer l’application

Démarrez Metro dans un terminal :

```sh
npm start
```

Dans un autre terminal, lancez l’application sur la plateforme souhaitée :

```sh
npm run android
```

ou :

```sh
npm run ios
```

Un émulateur/simulateur ou un appareil compatible doit être configuré. Consultez le [guide de configuration React Native](https://reactnative.dev/docs/set-up-your-environment) si nécessaire.

## Commandes utiles

```sh
npm start       # Démarrer Metro
npm run android # Construire et lancer sur Android
npm run ios     # Construire et lancer sur iOS
npm test        # Exécuter les tests
npm run lint    # Vérifier le code avec ESLint
```

## Technologies

- React Native CLI et TypeScript
- React Navigation
- Cible : Android et iOS

Pour en savoir plus sur React Native, consultez la [documentation officielle](https://reactnative.dev/docs/getting-started).
