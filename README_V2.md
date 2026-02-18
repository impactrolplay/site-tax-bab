# TAX & BAB Studio - Site Web

Ce dossier contient la nouvelle version du site pour **TAX & BAB Studio**, entièrement redesignée avec une esthétique "Agence Premium" en Bleu Foncé et Or.

## 🎨 Changements de Design
- **Palette de Couleurs** : Bleu Nuit Profond (`#050a14`) et Or Métallique (`#d4af37`).
- **Nouveau Layout** : Design asymétrique pour la section Hero avec des cartes flottantes animées.
- **Logo** : Intégration automatique de votre fichier `logo.png`.
- **Typographie** : Utilisation de polices modernes (Inter & Anton) pour un look professionnel.

## 🔑 Connexion Discord & Hébergement GitHub

### Peut-on héberger sur GitHub Pages gratuitement ?
**OUI**, vous pouvez héberger ce site (HTML/CSS/JS) gratuitement sur GitHub Pages.

### Concernant la connexion Discord :
Le bouton "Connexion" ajouté dans le header est actuellement un lien de démonstration.
Pour que la connexion fonctionne réellement (récupérer le pseudo, l'avatar, les rôles), vous avez deux options :

1.  **Option Simple (Sans Backend)** : Le bouton redirige simplement vers votre serveur Discord. C'est gratuit et fonctionne parfaitement sur GitHub Pages.
2.  **Option Avancée (Vraie Connexion OAuth2)** :
    - GitHub Pages est un hébergement *statique* (il ne peut pas exécuter de PHP ou de Python coté serveur).
    - Pour une vraie connexion sécurisée, vous aurez besoin d'un service tiers (comme **Firebase Authentication**, **Auth0**) ou d'une petite fonction serverless (comme **Vercel Functions** ou **Netlify Functions**).
    - **Recommandation** : Si vous voulez rester gratuit et simple, utilisez Netlify ou Vercel au lieu de GitHub Pages directement, car ils offrent des fonctions backend gratuites pour gérer la connexion Discord.

## 📁 Installation
1.  Assurez-vous que votre fichier logo se nomme bien `logo.png` et se trouve dans le même dossier que `index.html`.
2.  Ouvrez `index.html` pour modifier les liens et textes.
3.  Pour changer les images des projets, remplacez les liens `picsum.photos` par vos propres images dans le dossier.
