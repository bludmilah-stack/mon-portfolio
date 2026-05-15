# 🚀 Guide de Démarrage Rapide

## Étape 1: Préparer les fichiers

✅ Vous avez reçu:
- `index.html` - Page principale
- `styles.css` - Styles du site
- `script.js` - Interactivité
- `portfolio-config.json` - Configuration
- `README.md` - Documentation complète
- `netlify.toml` - Configuration Netlify

## Étape 2: Ajouter vos images (IMPORTANT!)

Créez un dossier `images/` et ajoutez:

```
images/
├── profile.jpg       ← Votre photo (recommandé: 300x300px ou plus)
├── logo.png         ← Optionnel: votre logo
├── tsitoro.jpg      ← Image du projet TSITORO
├── cye.jpg          ← Image du projet CYE
└── medpreneur.jpg   ← Image du projet MedPreneur
```

**💡 Conseil**: Optimisez vos images (compressez-les) pour un site plus rapide.

## Étape 3: Personnaliser vos réseaux sociaux

Ouvrez `index.html` et trouvez la section "social-links" (~ligne 168):

```html
<div class="social-links">
    <a href="https://facebook.com/VOTRE_PROFIL" target="_blank">
    <a href="https://linkedin.com/in/VOTRE_PROFIL" target="_blank">
    <a href="https://instagram.com/VOTRE_PSEUDO" target="_blank">
```

Remplacez les URLs par vos vrais profils.

## Étape 4: Tester localement

### Windows (Simple)
1. Double-cliquez sur `index.html`
2. Votre navigateur s'ouvre ✓

### Avec Live Server (Mieux)
1. Installez l'extension VS Code "Live Server"
2. Faites clic droit sur `index.html` → "Open with Live Server"
3. Le site se reload automatiquement quand vous modifiez ✓

## Étape 5: Déployer sur Netlify (GRATUIT!)

### La façon la plus simple (Drag & Drop):

1. Allez sur **[netlify.com](https://netlify.com)**
2. Cliquez sur **"Sign up"** (gratuit!)
3. Connectez-vous avec Google ou GitHub
4. **Drag & Drop** votre dossier portfolio sur Netlify
5. ✨ Boom! Votre site est en ligne!

Votre URL: `https://nom-random.netlify.app`

### Personnaliser votre domaine Netlify:

1. Dans Netlify, allez à **Site settings**
2. Cliquez sur **Change site name**
3. Entrez: `ludmilah-portfolio` (ou autre)
4. Votre nouveau lien: `https://ludmilah-portfolio.netlify.app`

## Étape 6: (Optionnel) Utiliser votre propre domaine

Si vous avez un domaine personnalisé (ex: ludmilah.mg):
1. Chez votre registraire DNS, pointez vers Netlify
2. Dans Netlify, ajoutez le domaine personnalisé
3. Documentation: [Netlify Domains](https://docs.netlify.com/domains-https/custom-domains/)

## 📝 Modifications courantes

### Changer les couleurs
Modifiez `styles.css` ligne 2-8:
```css
:root {
    --primary-color: #a855f7;     /* Purple */
    --secondary-color: #ec4899;   /* Pink */
}
```

### Ajouter un nouveau projet
Dupliquez un `<div class="project-card">` dans `index.html`

### Mettre à jour l'email
Cherchez `bludmilah@yahoo.com` dans `index.html` et remplacez

### Modifier le titre du navigateur
Dans `index.html` ligne 5:
```html
<title>Votre Nouveau Titre</title>
```

## 🐛 Problèmes courants

| Problème | Solution |
|----------|----------|
| Les images ne s'affichent pas | Vérifiez le dossier `images/` et les noms de fichiers |
| Le formulaire ne marche pas | Il ouvre votre email (Gmail, Outlook, etc.) - c'est normal! |
| Le site ne s'affiche pas | Vérifiez que `index.html` est à la racine |
| Les couleurs ne changent pas | Vérifiez l'orthographe dans `styles.css` |

## 📊 Prochaines étapes (Optionnel)

- [ ] Tester sur mobile (avec F12 → "Toggle Device Toolbar")
- [ ] Ajouter Google Analytics (voir README.md)
- [ ] Paramétrer un formulaire de contact avancé (FormSubmit.co)
- [ ] Ajouter un blog (Jekyll, Markdown)
- [ ] Optimiser les images avec Tinypng.com

## ✨ Conseils pro

1. **Gardez le contenu à jour** - Mettez à jour vos projets régulièrement
2. **Photos de qualité** - Investissez dans de bonnes images
3. **Contenu court** - Les visiteurs lisent en diagonale, soyez concis
4. **Mobile first** - Testez toujours sur mobile
5. **Linkez vers vos réseaux** - C'est important pour l'engagement

## 💬 Besoin d'aide?

- 📧 Email: bludmilah@yahoo.com
- 📚 Docs complètes: Voir `README.md`
- 🌐 Netlify Help: https://docs.netlify.com/

---

**Bon courage! 🎉 Votre portfolio sera en ligne en 5 minutes!**
