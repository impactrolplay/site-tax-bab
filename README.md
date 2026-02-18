# FS-DEVELOPMENT Website

Ce site a été créé selon vos spécifications pour FS-DEVELOPMENT. Il utilise HTML, CSS et JavaScript pur (Vanilla) pour une performance maximale et une modification facile.

## Structure du projet

- **index.html**: La structure principale du site. C'est ici que vous modifierez les textes, les titres et l'agencement.
- **style.css**: Le fichier de style qui gère les couleurs, la mise en page, les polices et le thème sombre "Premium".
- **script.js**: Gère les animations d'apparition et la barre de recherche.

## Comment personnaliser

### 1. Changer les images
Actuellement, le site utilise des images de remplissage (placeholders). Pour mettre vos propres images :
- Créez un dossier `images` dans ce répertoire.
- Ajoutez vos images (par exemple `telephone.jpg`, `logo.png`).
- Dans `index.html`, cherchez les balises `div` avec les classes `card-image` ou `character-placeholder`.
- Remplacez les styles `background: url(...)` ou ajoutez des balises `<img>` selon vos besoins.

### 2. Modifier les textes
Ouvrez `index.html` avec un éditeur de texte (comme Visual Studio Code) et modifiez le texte entre les balises. Par exemple, pour changer le titre "SCRIPTS FIVEM PREMIUM", cherchez simplement ce texte dans le fichier.

### 3. Ajouter des liens
Pour lier votre Discord ou d'autres pages, modifiez les attributs `href="#"` dans le menu de navigation ou les boutons :
```html
<a href="https://discord.gg/votre-lien" class="discord-btn">...</a>
```

## Technologies utilisées
- HTML5
- CSS3 (Variables, Flexbox, Grid, Animations)
- JavaScript (DOM Manipulation, Intersection Observer)
- FontAwesome (Icônes)
- Google Fonts (Inter, Anton)
