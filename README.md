# Portfolio Collectif – Groupe 2 (ULC-ICAM)

Ce projet est un site web moderne, élégant, professionnel et responsive, conçu sous forme de portfolio collectif pour présenter les profils, compétences, projets et parcours des 7 étudiants-ingénieurs du **Groupe 2 de l'ULC-ICAM (Université Loyola du Congo)**.

Le site est réalisé **exclusivement en HTML5 et CSS3**, sans aucun framework JavaScript, sans script externe, sans backend ni base de données requise.

---

## 🎨 Identité Visuelle et Charte Graphique

- **Bleu nuit** : `#14243A` (Couleur principale de fond sombre, contrastes et hero section)
- **Bleu profond** : `#233D5B` (Composants secondaires et dégradés)
- **Blanc cassé** : `#F7F8FA` (Fond général du site)
- **Gris clair** : `#E9EDF2` (Bordures, séparateurs et cartes secondaires)
- **Gris texte** : `#5D6875` (Textes descriptifs et typographie de lecture)
- **Accent doré discret** : `#C5A46D` (Accents, badges, puces et bordures d'honneur)

---

## 📁 Structure du Projet

```text
groupe2-portfolio/
│
├── index.html                   # Page d'accueil collective du Groupe 2
│
├── pages/                       # Les 7 pages individuelles de CV moderne
│   ├── lionel.html              # CV de CIRHUZA BARHOBAGAYANA LIONEL
│   ├── david.html               # CV de DAVID CRISTAL LANGA BONKETHI
│   ├── eredict.html             # CV de KALIMIRA CITONABINTU EREDICT
│   ├── merveille.html           # CV de MERVEILLE MFALA
│   ├── israel.html              # CV de ISRAËL KALESHI KYALONDAWA
│   ├── recodi.html              # CV de RECODI MAMANYA
│   └── joel.html                # CV de JOEL AMANI WENGA
│
├── css/
│   ├── style.css                # Styles globaux, hero, navigation responsive et grille
│   └── cv.css                   # Styles dédiés aux pages CV individuelles
│
├── assets/
│   ├── images/                  # Avatars SVG / photos remplaçables des 7 membres
│   │   ├── lionel.svg
│   │   ├── david.svg
│   │   ├── eredict.svg
│   │   ├── merveille.svg
│   │   ├── israel.svg
│   │   ├── recodi.svg
│   │   └── joel.svg
│   ├── projects/                # Schémas et illustrations techniques des 4 projets
│   │   ├── drone.svg            # Projet Drone (Aéronautique, suivi GPS)
│   │   ├── rallonge.svg         # Rallonge électrique & HydraOne
│   │   ├── amplificateur.svg    # Amplificateur de microphone
│   │   └── bateau.svg           # Projet Bateau naval
│   └── icons/                   # Répertoire pour icônes additionnelles
│
└── README.md                    # Documentation complète du projet
```

---

## 🚀 Caractéristiques & Fonctionnalités

1. **Pur HTML5 / CSS3** :
   - Aucun fichier JS ou dépendance externe.
   - Menu mobile responsive 100% CSS basé sur la technique du toggle checkbox accessible.
2. **Page d'accueil (`index.html`)** :
   - **Hero Section** : Titre *« Des idées, des compétences, des solutions. »*, statistiques d'équipe et appel à l'action.
   - **Section À propos** : Description officielle et présentation visuelle des 5 valeurs (*Innovation, Travail en équipe, Ingénierie, Créativité, Apprentissage*).
   - **Section Membres** : Grille responsive avec 7 cartes soignées, photos, badges de domaine et bouton « Voir le profil ».
   - **Section Projets techniques** : Respect strict des 4 catégories autorisées (*Projet Drone, Rallonge électrique, Amplificateur de microphone, Projet Bateau*) avec association fidèle des membres d'après les données sources.
   - **Section Compétences collectives** : 8 catégories complètes d'ingénierie et de technologies.
3. **7 Pages individuelles de CV moderne (`pages/*.html`)** :
   - **Discrétion et fidélité** : Données 100% issues des CV sources sans extrapolation ni invention.
   - **Structure des CV** : En-tête avec photo, nom très visible, coordonnées cliquables (`mailto:` et `tel:`), Profil, Formations chronologiques, Expériences/Stages, Projets avec rôles précis, Compétences par domaine (sans pourcentages arbitraires), Langues avec niveaux renseignés, Qualités personnelles, Distinctions et Centres d'intérêt.
   - **Navigation fluide** : Breadcrumb, bouton de retour direct vers l'équipe et liens séquentiels vers les profils suivants.

---

## 💻 Instructions de Lancement

1. Ouvrir le dossier racine `Portfolio Groupe 2` dans votre éditeur (ex: **VS Code**).
2. Double-cliquer directement sur `index.html` ou faire un clic droit > **Open with Live Server** (ou ouvrir dans n'importe quel navigateur web moderne : Chrome, Firefox, Edge, Safari).
3. Le site fonctionne hors ligne de manière autonome.
