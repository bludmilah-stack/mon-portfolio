# Portfolio - LUDMILAH Bien Venu

Bienvenue sur votre portfolio professionnel! 🎉

## 📋 Contenu

Un portfolio moderne et responsive présentant:
- ✨ Présentation personnelle
- 💼 Expérience professionnelle
- 🚀 Projets entrepreneuriaux
- 🛠️ Compétences
- 📧 Formulaire de contact

## 🎨 Design

- **Thème**: Moderne et sombre avec dégradés purple/pink
- **Responsive**: Fonctionne sur tous les appareils (mobile, tablette, desktop)
- **Performant**: Optimisé pour une chargement rapide
- **Accessible**: Code sémantique et accessible

## 📁 Structure

```
portfolio/
├── index.html      # Page principale
├── styles.css      # Styles CSS
├── script.js       # Logique JavaScript
├── images/         # Dossier pour vos images
│   ├── profile.jpg     # Votre photo de profil
│   ├── logo.png        # Logo (optionnel)
│   ├── tsitoro.jpg     # Image du projet TSITORO
│   ├── cye.jpg         # Image du projet CYE
│   └── medpreneur.jpg  # Image du projet MedPreneur
└── README.md       # Ce fichier
```

## 🚀 Déploiement sur Netlify

### Étape 1: Préparer vos images
1. Créez un dossier `images` dans le répertoire du portfolio
2. Ajoutez vos images:
   - `profile.jpg` - Votre photo de profil
   - `logo.png` - Votre logo (optionnel)
   - `tsitoro.jpg`, `cye.jpg`, `medpreneur.jpg` - Images de vos projets

### Étape 2: Mettre à jour les réseaux sociaux

Modifiez les URLs de vos réseaux dans `index.html`:

```html
<!-- Ligne ~168 - Remplacez les URLs -->
<a href="https://facebook.com/VOTRE_PROFIL" target="_blank" title="Facebook">
<a href="https://linkedin.com/in/VOTRE_PROFIL" target="_blank" title="LinkedIn">
<a href="https://instagram.com/VOTRE_PSEUDO" target="_blank" title="Instagram">
```

### Étape 3: Déployer sur Netlify (Facile!)

#### Option A: Drag & Drop (La plus simple)
1. Allez sur [netlify.com](https://netlify.com)
2. Connectez-vous avec votre compte (Google, GitHub, etc.)
3. Drag & Drop votre dossier portfolio
4. Voilà! Votre site est en ligne 🎉

#### Option B: Depuis GitHub
1. Créez un repository GitHub
2. Poussez vos fichiers:
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/VOTRE_USERNAME/VOTRE_REPO.git
git push -u origin main
```
3. Sur Netlify: "New site from Git" → Sélectionnez votre repo
4. Deployez! 🚀

#### Option C: Depuis le dossier local
1. Téléchargez [Git](https://git-scm.com)
2. Sur Netlify: "New site from Git" ou Drag & Drop

## 🔧 Personnalisation

### Changer les couleurs

Modifiez les variables CSS dans `styles.css`:

```css
:root {
    --primary-color: #a855f7;      /* Couleur primaire (purple) */
    --secondary-color: #ec4899;    /* Couleur secondaire (pink) */
    --dark-bg: #0f172a;            /* Fond sombre */
    /* ... autres couleurs ... */
}
```

### Ajouter/Modifier du contenu

- **À propos**: Modifiez le texte dans la section `<section id="about">`
- **Expérience**: Ajoutez des cartes dans `<div class="experience-grid">`
- **Projets**: Ajoutez des projets dans `<div class="projects-grid">`
- **Compétences**: Modifiez la section skills

### Ajouter des projets

Dupliquez cette structure dans `<div class="projects-grid">`:

```html
<div class="project-card">
    <div class="project-image">
        <img src="images/mon-projet.jpg" alt="Mon Projet">
    </div>
    <div class="project-content">
        <h3>Titre du Projet</h3>
        <p class="project-category">Catégorie</p>
        <p class="project-description">Description...</p>
        <div class="project-tags">
            <span>#Tag1</span>
            <span>#Tag2</span>
        </div>
        <button class="btn btn-secondary">En savoir plus</button>
    </div>
</div>
```

## 📱 Responsive Design

Le portfolio s'adapte automatiquement à:
- 📱 Mobile (480px et moins)
- 📱 Tablette (480px - 768px)
- 💻 Desktop (768px+)

## 🔒 Important

**Informations sensibles**: 
- N'exposez pas vos numéros de téléphone entièrement sur internet
- Utilisez des liens masqués si possible
- Envisagez un formulaire de contact plutôt que d'afficher directement vos coordonnées

## 🐛 Dépannage

**Les images ne s'affichent pas?**
- Vérifiez que le dossier `images/` existe
- Vérifiez que les noms de fichiers correspondent exactement
- Utilisez des chemins relatifs: `images/profile.jpg`

**Le formulaire de contact ne fonctionne pas?**
- Actuellement, il utilise `mailto:` (ouvre l'email client)
- Pour un vrai backend, utilisez FormSubmit.co ou Getform.io

**Le site n'est pas responsive?**
- Vérifiez que `<meta name="viewport"...>` est présent
- Testez avec la touche F12 et "Toggle Device Toolbar"

## 📞 Support

Pour toute question ou assistance:
- 📧 Email: bludmilah@yahoo.com
- 📱 Téléphone: +261 32 97 238 11

## 📄 Licence

Ce portfolio est libre d'utilisation. Vous pouvez le modifier et l'utiliser comme bon vous semble.

---

**Créé avec ❤️ pour LUDMILAH Bien Venu**

Dernière mise à jour: Mai 2026
