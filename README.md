# Site de la famille Célio

Site de partage et de mémoire de la famille Célio, généré avec [Cecil](https://cecil.app).

## Prévisualisation locale

Pour prévisualiser le site avec rechargement automatique :

```bash
php cecil.phar serve
```

Pour générer le site dans le dossier `_site/` :

```bash
php cecil.phar build
```

## Publication sur GitHub Pages

Le dépôt utilise GitHub Actions pour construire et publier le site à chaque envoi sur la branche `main` (ou `master`). Le site sera disponible à l’adresse :

<https://hopekyakwanda-tech.github.io/L3IAGE-IGAFE_2026/>

Dans GitHub, vérifiez que **Settings → Pages → Build and deployment → Source** est réglé sur **GitHub Actions**. Consultez ensuite l’onglet **Actions** pour suivre la publication.

## Contenu du dépôt

- `cecil.yml` : configuration du site
- `pages/` : pages et articles en Markdown
- `layouts/` : modèles Twig personnalisés
- `assets/` : images et styles du site
- `static/` : fichiers copiés sans modification
