# README.md

## Projet : Boutique en Ligne - Vente de Robes pour Femmes

### Description du Projet
Ce projet consiste en la création d'un site e-commerce utilisant WordPress, WooCommerce et WPForms. La boutique est spécialisée dans la vente de robes pour femmes, avec une interface utilisateur intuitive et des fonctionnalités avancées pour une expérience client optimale.

### Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants :
- **XAMPP** ou un autre serveur local (MAMP, WAMP).
- **PHP 7.4** ou une version supérieure.
- Une base de données MySQL.

### Installation

#### 1. Configuration du serveur local
1. Installez et lancez **XAMPP**.
2. Activez les services **Apache** et **MySQL**.

#### 2. Copier les fichiers du site
1. Téléchargez les fichiers source du site depuis ce dépôt.
2. Placez le dossier dans le répertoire `htdocs` de votre installation XAMPP (par exemple : `C:\xampp\htdocs\boutique_wp`).

#### 3. Importer la base de données
1. Accédez à [phpMyAdmin](http://localhost/phpmyadmin).
2. Créez une nouvelle base de données (par exemple : `boutique_wp`).
3. Importez le fichier SQL (situé dans le dossier `database` de ce dépôt) dans la base de données.

#### 4. Configurer WordPress
1. Ouvrez le fichier `wp-config.php` dans un éditeur de texte.
2. Modifiez les lignes suivantes avec vos informations de base de données :
   ```php
   define('DB_NAME', 'boutique_wp');
   define('DB_USER', 'root');
   define('DB_PASSWORD', '');
   define('DB_HOST', 'localhost');
   ```

#### 5. Accéder au site
1. Rendez-vous à `http://localhost/boutique_wp` dans votre navigateur.
2. Connectez-vous avec les identifiants administrateur ci-dessous.

### Identifiants Administrateur
- **Nom d'utilisateur** : admin
- **Mot de passe** : admin123

### Fonctionnalités du Site
- **WooCommerce** : Gestion des produits, panier, et paiement.
- **WPForms** : Formulaire de contact personnalisé.
- **Pages principales** :
  - Accueil
  - Boutique
  - Contact
  - À propos

### Structure des Fichiers
- `htdocs/boutique_wp` : Contient les fichiers WordPress et les extensions.
- `database/boutique_wp.sql` : Fichier d'export de la base de données.

### Support
Pour toute question ou problème, veuillez nous contacter 
### Fichier `.zip`

Le fichier `.zip` est trop volumineux pour être téléchargé directement sur GitHub. Vous pouvez le télécharger via Google Drive à l'adresse suivante : [Télécharger le fichier](https://drive.google.com/file/d/1-a7mCgaFUt4vns24u5OtQgJWNEI9joGn/view?usp=sharing)


