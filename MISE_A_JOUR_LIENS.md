# 🔗 Mise à Jour des Liens Sociaux

## Où mettre à jour vos URLs

Ouvrez `index.html` et trouvez ces sections:

### 1. Section "À propos" (Ligne ~168)
```html
<div class="social-links">
    <a href="https://facebook.com" target="_blank" title="Facebook">
    <a href="https://linkedin.com" target="_blank" title="LinkedIn">
    <a href="https://instagram.com" target="_blank" title="Instagram">
    <a href="mailto:bludmilah@yahoo.com" title="Email">
</div>
```

### 2. Section "Contact" (Ligne ~284)
```html
<a href="https://facebook.com" target="_blank">
<a href="https://linkedin.com" target="_blank">
<a href="https://instagram.com" target="_blank">
```

---

## 📱 Comment obtenir vos URLs

### Facebook
1. Allez sur [facebook.com](https://facebook.com)
2. Allez à votre profil
3. Copiez l'URL: `https://facebook.com/VOTRE_USERNAME`

### LinkedIn
1. Allez sur [linkedin.com](https://linkedin.com)
2. Visitez votre profil
3. Copiez l'URL: `https://linkedin.com/in/VOTRE_PROFIL`

### Instagram
1. Allez sur [instagram.com](https://instagram.com)
2. Allez à votre profil
3. Copiez l'URL: `https://instagram.com/VOTRE_USERNAME`

### GitHub (Optionnel)
1. Allez sur [github.com](https://github.com)
2. Allez à votre profil
3. Copiez l'URL: `https://github.com/VOTRE_USERNAME`

### Twitter/X (Optionnel)
1. Allez sur [twitter.com](https://twitter.com)
2. Allez à votre profil
3. Copiez l'URL: `https://twitter.com/VOTRE_USERNAME`

---

## 📧 Email & Téléphone

Ces informations sont déjà mises à jour:
- ✅ Email: `bludmilah@yahoo.com`
- ✅ Téléphone: `+261 32 97 238 11`
- ✅ Adresse: `Ambalavola Lot 115 Plle 421`

Si vous voulez les changer, cherchez ces valeurs dans `index.html`.

---

## ⚙️ Configuration JSON (Optionnel)

Vous pouvez aussi mettre à jour `portfolio-config.json`:

```json
"socials": {
    "facebook": "https://facebook.com/VOTRE_PROFIL",
    "linkedin": "https://linkedin.com/in/VOTRE_PROFIL",
    "instagram": "https://instagram.com/VOTRE_USERNAME",
    "github": "https://github.com/VOTRE_USERNAME",
    "twitter": "https://twitter.com/VOTRE_USERNAME"
}
```

---

## ✨ Format des URLs

- ✅ `https://facebook.com/ludmilah`
- ✅ `https://linkedin.com/in/ludmilah-bien-venu`
- ❌ `facebook.com/ludmilah` (sans https://)
- ❌ `https://www.facebook.com/...` (www n'est pas nécessaire mais OK)

---

## 🔒 Sécurité

- N'exposez pas votre **numéro de téléphone personnel** entièrement
- Envisagez d'utiliser un **formulaire de contact** au lieu d'exposer votre email
- Vérifiez vos **paramètres de confidentialité** sur les réseaux

---

## 🚀 Après la mise à jour

1. Sauvegardez le fichier `index.html`
2. Testez les liens en cliquant dessus
3. Vérifiez que ça vous redirige vers le bon profil
4. Poussez les changements vers Netlify

---

**Besoin d'aide?** Voir `README.md` ou `GETTING_STARTED.md`
