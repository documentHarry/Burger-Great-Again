# 🍔 Burger Great Again

Site web vitrine pour un restaurant de burgers proposant des créations XXL avec des ingrédients de qualité.

## 📋 Description

Burger Great Again est un site web statique développé en HTML et CSS pur, sans framework. Le site présente un restaurant de burgers avec une identité forte : des burgers de taille XXL, des ingrédients de qualité et des prix honnêtes.

## ✨ Fonctionnalités

- **Page d'accueil** : Présentation du concept et des valeurs du restaurant
- **Produits** : Catalogue des burgers et menus disponibles
- **Nos Valeurs** : Présentation de la philosophie et des engagements
- **Commande** : Formulaire de commande en ligne
- **Nous Trouver** : Informations de localisation et contact

## 🏗️ Structure du projet

```
BurgerGreatAgain/
│
├── index.html              # Page d'accueil
├── produits.html           # Page des produits
├── nos-valeurs.html        # Page des valeurs
├── commande.html           # Page de commande
├── nous-trouver.html       # Page de localisation
│
└── css/
    ├── variables.css       # Variables CSS (couleurs, polices, etc.)
    ├── base.css            # Styles de base et reset
    ├── layout.css          # Structure et mise en page globale
    ├── header.css          # Styles du header/navigation
    ├── footer.css          # Styles du footer
    ├── title.css           # Styles des titres
    ├── buttons.css         # Styles des boutons
    ├── animations.css      # Animations et transitions
    ├── index.css           # Styles spécifiques page d'accueil
    ├── produits.css        # Styles spécifiques page produits
    ├── nos-valeurs.css     # Styles spécifiques page valeurs
    ├── commande.css        # Styles spécifiques page commande
    ├── nous-trouver.css    # Styles spécifiques page localisation
    └── responsive.css      # Media queries pour mobile/tablette
```

## 🎨 Architecture CSS

Le projet suit une architecture CSS modulaire et maintenable :

1. **Variables** : Définition des couleurs, typographies et espacements
2. **Base** : Reset CSS et styles globaux
3. **Layout** : Structure de page réutilisable
4. **Composants** : Header, footer, boutons, titres (réutilisables)
5. **Pages** : Styles spécifiques à chaque page
6. **Responsive** : Adaptations mobile et tablette (toujours chargé en dernier)

### Ordre de chargement des CSS

L'ordre de chargement est important pour éviter les conflits :

```html
<!-- 1. Variables CSS -->
<link rel="stylesheet" href="css/variables.css">
<!-- 2. Base -->
<link rel="stylesheet" href="css/base.css">
<!-- 3. Layout -->
<link rel="stylesheet" href="css/layout.css">
<!-- 4. Composants majeurs -->
<link rel="stylesheet" href="css/header.css">
<link rel="stylesheet" href="css/footer.css">
<!-- 5. Composants réutilisables -->
<link rel="stylesheet" href="css/title.css">
<link rel="stylesheet" href="css/buttons.css">
<link rel="stylesheet" href="css/animations.css">
<!-- 6. Page spécifique -->
<link rel="stylesheet" href="css/[nom-page].css">
<!-- 7. Responsive (TOUJOURS EN DERNIER) -->
<link rel="stylesheet" href="css/responsive.css">
```

## 🚀 Installation et utilisation

### Prérequis

Aucun prérequis technique particulier. Un navigateur web moderne suffit.

### Installation

1. Téléchargez ou clonez le projet
2. Extrayez les fichiers si nécessaire
3. Ouvrez `index.html` dans votre navigateur

### Utilisation locale

Ouvrez simplement le fichier `index.html` dans votre navigateur préféré. Aucun serveur web n'est nécessaire pour consulter le site en local.

### Déploiement

Pour déployer le site en production :

1. Uploadez tous les fichiers sur votre hébergeur web
2. Assurez-vous que la structure des dossiers est préservée
3. Le fichier `index.html` doit être à la racine

Le site est compatible avec tous les hébergeurs web statiques (GitHub Pages, Netlify, Vercel, etc.)

## 📱 Responsive Design

Le site est entièrement responsive et s'adapte automatiquement aux différentes tailles d'écran :

- **Desktop** : Affichage complet avec toutes les fonctionnalités
- **Tablette** : Layout adapté pour une consultation confortable
- **Mobile** : Navigation optimisée et contenu réorganisé

## 🎯 Choix techniques

- **HTML5 sémantique** : Utilisation des balises appropriées (header, nav, main, section, article, aside, footer)
- **CSS pur** : Aucune dépendance externe, pas de framework
- **Architecture modulaire** : CSS organisé en fichiers logiques et réutilisables
- **SVG inline** : Utilisation de SVG pour les images placeholders
- **Mobile-first** : Approche responsive prioritaire

## 🎨 Palette de couleurs

Les couleurs principales sont définies dans `css/variables.css` et peuvent être personnalisées facilement.

## 📄 Pages du site

### Accueil (`index.html`)
- Hero section avec call-to-action
- Présentation des avantages (Taille XXL, Qualité Premium, Prix Honnêtes)
- Section philosophie
- Offre du moment

### Produits (`produits.html`)
- Catalogue des burgers
- Menus et accompagnements
- Descriptions et prix

### Nos Valeurs (`nos-valeurs.html`)
- Présentation des engagements
- Origine des produits
- Démarche qualité

### Commande (`commande.html`)
- Formulaire de commande
- Sélection des produits
- Informations de livraison

### Nous Trouver (`nous-trouver.html`)
- Adresse et coordonnées
- Horaires d'ouverture
- Carte de localisation

## 🔧 Maintenance et personnalisation

### Modifier les couleurs

Éditez le fichier `css/variables.css` pour changer la palette de couleurs.

### Ajouter une nouvelle page

1. Créez un nouveau fichier HTML (ex: `nouvelle-page.html`)
2. Copiez la structure d'une page existante
3. Créez un fichier CSS dédié dans le dossier `css/`
4. Ajoutez le lien dans la navigation de toutes les pages

### Modifier le contenu

Le contenu est directement éditable dans les fichiers HTML. Aucune connaissance technique avancée n'est nécessaire.

## 🌐 Compatibilité navigateurs

Le site est compatible avec :
- Chrome/Edge (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Opera (dernières versions)

## 📝 Licence

Tous droits réservés © 2025 Burger Great Again

## 👤 Auteur

Francis Harry

Site développé en HTML/CSS pur

---

**Bon appétit ! 🍔**
