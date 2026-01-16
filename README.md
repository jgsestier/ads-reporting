# Dashboard Social Média — L'Aventure du Sucre

## 🚀 Déploiement sur Vercel (3 méthodes)

### Méthode 1 : Via GitHub (recommandée)

1. Crée un nouveau repository sur GitHub
2. Dézippe ce dossier et push le contenu
3. Va sur [vercel.com](https://vercel.com)
4. Clique sur "Add New Project"
5. Importe ton repository GitHub
6. Clique sur "Deploy" — c'est tout !

### Méthode 2 : Drag & Drop (la plus rapide)

1. Dézippe ce dossier
2. Ouvre un terminal dans le dossier
3. Lance `npm install` puis `npm run build`
4. Va sur [vercel.com](https://vercel.com)
5. Glisse-dépose le dossier `dist/` généré
6. C'est en ligne !

### Méthode 3 : Vercel CLI

```bash
# Installer Vercel CLI si pas déjà fait
npm install -g vercel

# Dans le dossier du projet
npm install
vercel
```

## 📁 Structure du projet

```
vercel-dashboard/
├── src/
│   ├── App.jsx          # Composant principal du dashboard
│   ├── main.jsx         # Point d'entrée React
│   └── index.css        # Styles Tailwind
├── public/
│   └── favicon.svg      # Icône du site
├── index.html           # Page HTML
├── package.json         # Dépendances
├── vite.config.js       # Config Vite
├── tailwind.config.js   # Config Tailwind
└── postcss.config.js    # Config PostCSS
```

## 🛠 Développement local

```bash
# Installer les dépendances
npm install

# Lancer le serveur de développement
npm run dev

# Le site sera accessible sur http://localhost:5173
```

## 📝 Personnalisation

Pour modifier les données du dashboard, édite le fichier `src/App.jsx` et modifie les objets de données au début du composant (platformComparison, categoryDataFB, etc.)

---

Créé pour L'Aventure du Sucre — 2025
