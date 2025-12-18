# 🏭 Site Web AKA France

Site web vitrine pour **AKA France** - Alliance of Knowledge & Accuracy.  
Partenaire industriel franco-chinois depuis 30 ans.

---

## 📁 Structure du projet

```
aka-france-site/
├── index.html          # Page principale du site
├── favicon.svg         # Favicon (icône du site)
├── images/
│   └── logo-aka.png    # Logo AKA France
└── README.md           # Ce fichier
```

---

## 🚀 Déployer sur GitHub Pages (gratuit)

### Étape 1 : Créer un compte GitHub

1. Va sur [github.com](https://github.com)
2. Clique sur **"Sign up"**
3. Suis les instructions pour créer ton compte

### Étape 2 : Créer un nouveau repository

1. Une fois connecté, clique sur le **"+"** en haut à droite
2. Sélectionne **"New repository"**
3. Donne un nom : `aka-france` (ou ce que tu veux)
4. Laisse **"Public"** sélectionné
5. **NE COCHE PAS** "Add a README file" (on a déjà le nôtre)
6. Clique sur **"Create repository"**

### Étape 3 : Téléverser les fichiers

**Méthode simple (via l'interface web) :**

1. Sur la page de ton nouveau repository, clique sur **"uploading an existing file"**
2. Glisse-dépose **TOUS les fichiers** du dossier `aka-france-site` :
   - `index.html`
   - `favicon.svg`
   - Le dossier `images/` avec `logo-aka.png`
3. En bas, écris un message comme "Premier upload du site"
4. Clique sur **"Commit changes"**

### Étape 4 : Activer GitHub Pages

1. Va dans **Settings** (onglet en haut du repository)
2. Dans le menu à gauche, clique sur **"Pages"**
3. Sous **"Source"**, sélectionne **"Deploy from a branch"**
4. Sous **"Branch"**, sélectionne **"main"** et **"/ (root)"**
5. Clique sur **"Save"**

### Étape 5 : Attendre et accéder au site

- Attends 1-2 minutes que GitHub déploie le site
- Ton site sera accessible à : `https://TON-NOM-UTILISATEUR.github.io/aka-france/`
- Tu peux voir l'URL exacte dans **Settings > Pages**

---

## ✏️ Modifier le site

### Changer les informations de contact

Dans `index.html`, cherche la section `<!-- Contact -->` et modifie :

```html
<p class="value">contact@aka-france.com</p>  <!-- Email -->
<p class="value">+33 (0)2 XX XX XX XX</p>    <!-- Téléphone -->
<p class="value">Nantes, France</p>           <!-- Adresse -->
```

### Modifier les textes

Tous les textes sont dans `index.html`. Tu peux les modifier directement sur GitHub :

1. Clique sur `index.html`
2. Clique sur l'icône ✏️ (crayon) en haut à droite
3. Modifie le texte
4. Clique sur **"Commit changes"**
5. Le site se met à jour automatiquement en 1-2 minutes

---

## 🎨 Personnalisation

### Couleurs principales

Les couleurs sont définies au début du CSS (dans `<style>`) :

```css
:root {
    --aka-red: #c41e24;      /* Rouge AKA */
    --aka-brown: #4a3728;    /* Marron AKA */
    --cream: #faf8f5;        /* Fond clair */
}
```

### Ajouter des images

1. Mets tes images dans le dossier `images/`
2. Référence-les dans le HTML : `<img src="images/nom-image.jpg">`

---

## 🌐 Nom de domaine personnalisé (optionnel)

Si tu veux utiliser `www.aka-france.com` au lieu de `github.io` :

1. Achète un nom de domaine (OVH, Gandi, etc.)
2. Dans GitHub **Settings > Pages**, entre ton domaine dans **"Custom domain"**
3. Configure les DNS chez ton registrar :
   - Type A vers `185.199.108.153`
   - Type A vers `185.199.109.153`
   - Type A vers `185.199.110.153`
   - Type A vers `185.199.111.153`

---

## 🆘 Besoin d'aide ?

- **Documentation GitHub Pages** : https://docs.github.com/en/pages
- **Tutoriels vidéo** : Cherche "GitHub Pages tutorial" sur YouTube

---

Bonne chance avec le site ! 🚀
