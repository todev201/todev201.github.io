# Portfolio — Oumar TRAORÉ (V1)

Site statique responsive, **FR/EN**, sans installation de framework : HTML, CSS, JavaScript.

## Lancer localement

Ouvrir `index.html` dans un navigateur, ou, avec Python :

```bash
cd oumar-portfolio
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## Publication gratuite

- **GitHub Pages** : créer un dépôt, ajouter les fichiers à la racine, puis Settings → Pages → Deploy from branch → main / root.
- **Netlify** : glisser-déposer le dossier `oumar-portfolio` sur le déploiement manuel Netlify.
- **Cloudflare Pages** : créer un projet de site statique puis envoyer ce dossier.

Le domaine personnalisé reste à décider.

## Fichiers

- `index.html` : structure des sections et accessibilité.
- `styles.css` : identité sombre premium et responsive.
- `script.js` : contenus bilingues et fiches projet interactives.
- `assets/` : portrait, illustrations conceptuelles et CV.

## Important avant publication

- Les images de projets sont des **maquettes générées**, **pas des captures authentiques**. Les chiffres et personnes visibles dans ces images sont fictifs. Les éléments exacts et la lisibilité doivent être revus avant publication.
- Les noms et descriptions des quatre projets clients (Yogurt Olumten, StockManager+, ERP SCOOP Maïda et Gestion des ordres de mission) exigent une validation des droits de publication. Retirer les fiches concernées au besoin avant mise en ligne.
- Vérifier les textes des expériences, les périodes et le niveau exact d'implication.
- Le téléchargement du CV publie les coordonnées qu'il contient, notamment le numéro de téléphone. Pour un site public, utiliser une **version expurgée** du CV si nécessaire.
- Le bouton de contact utilise `mailto:` : pas de collecte des données sur un serveur.
- Les polices sont chargées depuis Google Fonts ; une police système de secours est prévue.

## Prochaines améliorations

SEO avancé, métadonnées de partage, formulaire de contact protégé, URL individuelle par étude de cas, accessibilité et tests multi-navigateurs, gestion d'un nom de domaine.
