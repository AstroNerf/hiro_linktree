# LinkTree Clone - Hiver 2025
<img width="1431" alt="Capture d’écran 2025-04-10 à 18 27 39" src="https://github.com/user-attachments/assets/8b4b8abc-ed1f-46ce-978b-85358a5f6de5" />
Salut la team ! 👋

Voici ma version du projet Linktree de cette saison hiver 2025. Ce projet a été réalisé en pure HTML & CSS sans aucune autre stack ! Je t'invite à explorer le code pour y découvrir les bonnes pratiques (clean code) & des astuces de développement version senior web dev ^^

## Spécifications techniques
Ce projet respecte scrupuleusement les exigences suivantes :

• **Technologies autorisées** : Uniquement HTML & CSS
  - Aucun autre langage de programmation n'est autorisé
  - Aucune librairie ou framework externe n'est permis
  - Séparation stricte: le CSS doit être exclusivement dans des fichiers externes (.css)

• **Approche de conception** :
  - Développement Mobile-First obligatoire
  - Design entièrement responsive (jusqu'aux écrans 2XL)
  - Interface "no-scrolling" (tout le contenu visible sans défilement)

• **Éléments obligatoires** à inclure :
  - 1 image minimum
  - 1 titre principal
  - 1 sous-titre explicatif
  - 3 boutons interactifs minimum
  - 3 icônes distinctes minimum
  - 1 zone de navigation
  - 1 pied de page (footer)

• **Structure HTML requise** :
  - Utilisation des balises sémantiques essentielles: `<head>`, `<header>`, `<main>`, `<footer>`
  - Organisation logique avec `<div>`, `<section>` ou autres balises structurantes appropriées

• **Fonctionnalités CSS avancées** :
  - Minimum 3 animations distinctes
  - Minimum 3 micro-interactions/micro-actions différentes
  - Utilisation obligatoire de Flexbox et/ou Grid pour la mise en page

• **Conformité technique** :
  - Code intégralement validé selon les standards W3C
  - Attention: une seule erreur de validation = échec du projet (0/40 points)
  - Respect des meilleures pratiques de développement web (clean code)

• **Direction artistique** :
  - Choix imposé parmi 4 styles de design: Futurisme, Glassmorphisme, Pixel Art ou Design Asymétrique
  - Influences autorisées: Neumorphisme et Minimalisme comme inspirations complémentaires

## Déploiement :

Projet déployé avec [Surge](https://surge.sh), une plateforme d'hébergement statique ultra-rapide
- Surge.sh offre un déploiement simplifié via ligne de commande en une seule commande
- Solution idéale pour les projets HTML/CSS purs grâce à sa gratuité, sa simplicité d'utilisation et ses performances élevées
- Permet d'obtenir un URL public personnalisable instantanément sans configuration complexe
[Version Beta](https://hiro-tree.surge.sh)

## Organisation des fichiers
<img width="1238" alt="Capture d’écran 2025-04-10 à 18 49 13" src="https://github.com/user-attachments/assets/5538664e-a350-445c-9709-e4ec960d671a" />
J'ai organisé ce repo pour vous faciliter la vie et vous introduire aux bonnes pratiques d'architecture CSS :

```
index.html                  → Le fichier HTML principal déjà connecté au CSS
style.css                   → Le fichier CSS principal qui importe toutes les variables
│
├── assets/                 → Contient toutes les ressources statiques
│   ├── images/             → Pour stocker vos images & icônes
│   └── fonts/              → Polices personnalisées (déjà chargées depuis fontspace.com)
│
└── styles/                 → Organisation modulaire de votre CSS
    ├── all_variables.css   → Le point central qui importe tous les fichiers de variables
    ├── fonts.css           → Variables de typographie & chargement des polices
    ├── colors.css          → Palette de couleurs sous forme de variables
    ├── animations.css      → Transitions & animations réutilisables
    ├── layout.css          → Variables pour conteneurs, espacements, breakpoints, etc.
    └── boutons.css         → Composants de boutons prêts à l'emploi
```

## Comment contribuer à ce projet ?

Que vous souhaitiez ajouter des fonctionnalités, corriger des bugs ou simplement améliorer la structure, votre contribution est la bienvenue ! Deux approches s'offrent à vous :

### Option 1 : Cloner le repository

Le clonage crée une copie locale du projet que vous pouvez modifier tout en gardant un lien avec le repository original.

```bash
# Dans votre terminal
git clone git@github.com:AstroNerf/hiro_linktree.git
cd hiro_linktree

# Créez une nouvelle branche pour vos modifications
git checkout -b ma-nouvelle-fonctionnalite

# Après avoir fait vos modifications
git add .
git commit -m "Ajout de ma super fonctionnalité"
git push origin ma-nouvelle-fonctionnalite
```

Ensuite, rendez-vous sur GitHub pour créer une Pull Request afin que vos modifications puissent être revues et intégrées au projet principal.

### Option 2 : Forker le repository

Le fork crée votre propre copie du projet sur votre compte GitHub, vous donnant une liberté totale pour l'adapter à vos besoins.

1. Cliquez sur le bouton "Fork" en haut à droite de la page du repository
2. Clonez VOTRE version du repository sur votre machine
3. Faites vos modifications
4. Si vous souhaitez partager vos améliorations avec le projet original, créez une Pull Request depuis votre fork

## Pour démarrer rapidement

```bash
# Clonez le repository
git clone git@github.com:AstroNerf/hiro_linktree.git

# Accédez au dossier du projet
cd hiro_linktree

# Ouvrez le projet dans VS Code (si vous l'utilisez)
code .

# Ou simplement ouvrez index.html dans votre navigateur préféré
```

À partir de là, vous pouvez commencer à personnaliser ce Linktree en modifiant le HTML et le CSS selon vos besoins.

N'hésitez pas à explorer les fichiers de variables CSS pour comprendre comment ils sont organisés & comment les utiliser au mieux dans votre projet.

Bon coding à tou·te·s ! 💻✨
