Voici un `README.md` plus détaillé et bien structuré pour ton projet :

```markdown
# GMod Loading Screen Creator

![GMod Loading Screen Creator](https://example.com/image/logo.png) <!-- Remplace par l'URL de ton logo ou image de couverture -->

GMod Loading Screen Creator est une application web conçue pour permettre aux utilisateurs de créer facilement des écrans de chargement personnalisés pour Garry's Mod. Ce projet utilise Node.js, Express, EJS pour le rendu des vues, et MySQL pour la gestion des données.

## Table des Matières

- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du Projet](#structure-du-projet)
- [Déploiement](#déploiement)
- [Contribuer](#contribuer)
- [Licence](#licence)
- [Auteurs](#auteurs)
- [Remerciements](#remerciements)

## Prérequis

Avant de commencer, assurez-vous que les éléments suivants sont installés sur votre machine :

- [Node.js](https://nodejs.org/) (version 14 ou supérieure)
- [MySQL](https://www.mysql.com/)

## Installation

Suivez ces étapes pour installer et configurer l'application sur votre machine locale :

1. **Clonez le Repository**

   Utilisez Git pour cloner le repository sur votre machine :

   ```bash
   git clone https://github.com/ton-utilisateur/gmod-loading-screen.git
   ```

2. **Accédez au Répertoire du Projet**

   Déplacez-vous dans le répertoire du projet :

   ```bash
   cd gmod-loading-screen
   ```

3. **Installez les Dépendances**

   Installez les dépendances nécessaires avec npm :

   ```bash
   npm install
   ```

4. **Configurez les Variables d’Environnement**

   Créez un fichier `.env` à la racine du projet et ajoutez les variables suivantes avec vos propres valeurs :

   ```env
   DB_HOST=localhost
   DB_USER=ton-utilisateur
   DB_PASSWORD=ton-mot-de-passe
   DB_NAME=nom_de_la_base_de_donnees
   SESSION_PASSWORD=ta_clé_secrète
   PORT=3000
   ```

## Utilisation

Pour démarrer l'application et accéder à l'interface web :

1. **Démarrez l’Application**

   Lancez l'application en utilisant la commande suivante :

   ```bash
   npm start
   ```

2. **Accédez à l’Application**

   Ouvrez votre navigateur et accédez à `http://localhost:3000` pour utiliser l'interface de création d'écrans de chargement.

   ![Application Screenshot](https://example.com/image/screenshot.png) <!-- Remplace par l'URL de la capture d'écran de ton application -->

## Structure du Projet

Voici un aperçu de la structure du projet pour mieux comprendre son organisation :

- **`/public`** : Contient les fichiers statiques tels que les fichiers CSS, JavaScript et images.
- **`/routes`** : Contient les fichiers de routes pour gérer les différentes parties de l'application.
- **`/views`** : Contient les fichiers EJS utilisés pour le rendu des vues HTML.
- **`index.js`** : Le point d'entrée principal de l'application, où l'application Express est configurée et démarrée.

![Project Structure](https://example.com/image/project-structure.png) <!-- Remplace par l'URL d'une image montrant la structure du projet -->

## Déploiement

Pour déployer l'application sur un serveur comme Pterodactyl, suivez ces étapes :

1. **Téléversez les Fichiers**

   Utilisez le panneau de contrôle de Pterodactyl pour téléverser les fichiers de votre projet.

2. **Configurez les Variables d’Environnement**

   Dans le panneau de contrôle de Pterodactyl, ajoutez les variables d'environnement nécessaires :

   - `DB_HOST`
   - `DB_USER`
   - `DB_PASSWORD`
   - `DB_NAME`
   - `SESSION_PASSWORD`

3. **Définissez le Script de Démarrage**

   Configurez le script de démarrage dans Pterodactyl pour utiliser la commande suivante :

   ```bash
   npm start
   ```

4. **Démarrez l’Application**

   Lancez l'application depuis le panneau de contrôle de Pterodactyl.

   ![Pterodactyl Dashboard](https://example.com/image/pterodactyl-dashboard.png) <!-- Remplace par l'URL d'une capture d'écran du tableau de bord Pterodactyl -->

## Contribuer

Les contributions sont les bienvenues ! Voici comment vous pouvez contribuer au projet :

1. **Forkez le Repository**

2. **Créez une Nouvelle Branche**

   ```bash
   git checkout -b nom-de-ta-branche
   ```

3. **Effectuez vos Modifications**

4. **Committez vos Changements**

   ```bash
   git commit -am 'Ajoute une nouvelle fonctionnalité'
   ```

5. **Poussez votre Branche**

   ```bash
   git push origin nom-de-ta-branche
   ```

6. **Ouvrez une Pull Request**

   Ouvrez une pull request pour proposer vos modifications au projet principal.

## Licence

Ce projet est sous la licence [MIT](LICENSE). Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Auteurs

- **Ton Nom** - [ton-utilisateur](https://github.com/ton-utilisateur)

## Remerciements

- Merci à [Express](https://expressjs.com/) pour le framework web.
- Merci à [EJS](https://www.npmjs.com/package/ejs) pour le moteur de templates.
- Merci à [mysql2](https://www.npmjs.com/package/mysql2) pour l'intégration avec MySQL.
- Merci à [Pterodactyl](https://pterodactyl.io/) pour l'hébergement de l'application.
```

N'oublie pas de remplacer les placeholders comme les URLs des images et les informations spécifiques au projet avec les valeurs pertinentes. Si tu as des ajustements ou des ajouts spécifiques, fais-le moi savoir !
