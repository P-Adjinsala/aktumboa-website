# ◈ AktuMboa — Participation Citoyenne au Cameroun
### Site web officiel de l'application mobile AktuMboa

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_NETLIFY_BADGE/deploy-status)](https://app.netlify.com)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Deployed-Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)

---

## Présentation

Site web de présentation de **AktuMboa**, une application mobile de participation citoyenne développée dans le cadre de l'initiative **CitizenLab Cameroun** portée par **AfricTivistes**.

L'application vise à faciliter l'accès à l'information civique, encourager l'engagement des jeunes et promouvoir la transparence dans la gouvernance publique au Cameroun.

---

## Structure du projet

```
aktumboa/
├── index.html          ← Page principale (landing page)
├── netlify.toml        ← Configuration déploiement Netlify
├── assets/
│   ├── css/
│   │   └── style.css   ← Styles complets
│   └── js/
│       └── app.js      ← Interactions & animations
└── README.md
```

---

## Sections du site

| Section | Description |
|---------|-------------|
| **Hero** | Présentation principale avec mockup téléphone animé |
| **Fonctionnalités** | 6 fonctionnalités en grille bento |
| **Comment ça marche** | 3 étapes d'utilisation |
| **Impact** | 4 impacts attendus de l'application |
| **À propos** | Contexte AfricTivistes CitizenLab |
| **Téléchargement** | Liens stores + formulaire de notification |

---

## Déploiement sur Netlify

### Option A — Drag & drop (le plus rapide)
1. Allez sur [netlify.com](https://netlify.com) → **Log in**
2. Glissez le dossier `aktumboa/` dans la zone de déploiement
3. Le site est en ligne en 30 secondes ✅

### Option B — Via GitHub (recommandé)
1. Poussez ce repo sur GitHub
2. Netlify → **New site from Git** → connectez le repo
3. Build command : *(laisser vide)*
4. Publish directory : `.`
5. **Deploy site** ✅

### Option C — Vercel
```bash
npm i -g vercel
cd aktumboa
vercel
```

---

## Stack technique

- **HTML5** sémantique, sans framework
- **CSS3** pur — variables CSS, Grid, Flexbox, animations
- **JavaScript** vanilla — IntersectionObserver, smooth scroll
- **Google Fonts** — Bebas Neue + Outfit
- **Zero dépendances npm** — déploiement immédiat

---

## Contexte du projet

AktuMboa a été conçue et développée au sein de l'initiative **AfricTivistes CitizenLab Cameroun**.  
Ce site web a été réalisé par **Pantouin Adjinsala** dans le cadre de ses contributions civic tech.

**Organisation :** [AfricTivistes](https://africTivistes.org)  
**Auteur :** [Pantouin Adjinsala](https://github.com/P-Adjinsala)  
**Partie du portfolio :** [AI for Social Good & Civic Tech](https://github.com/P-Adjinsala)
