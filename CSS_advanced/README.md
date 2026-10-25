# CSS Advanced

Exercices de CSS réalisés dans le cadre du programme Holberton School. Ce
dossier contient une série de feuilles de style progressives et les images
utilisées pour construire le site vitrine fictif **Techium**.

## Contenu

```text
CSS_advanced/
├── images/             # Logos, photos et favicon
├── styles/             # Étapes de réalisation des styles CSS
└── README.md
```

Les fichiers `styles/*-style.css` présentent les étapes successives du
travail : couleurs, typographie, variables CSS, composants, espacements et
mises en page. Le fichier `24.style.css` conserve son nom tel qu'il existe
dans le projet.

## Aperçu

Ce dossier ne contient pas de page HTML. Les pages de démonstration sont dans
[`../html_advanced/`](../html_advanced/). Pour afficher une feuille de style
avec l'une de ces pages, ajoutez dans son élément `<head>` un lien vers la
feuille souhaitée, par exemple :

```html
<link rel="stylesheet" href="../CSS_advanced/styles/16-style.css">
```

Depuis la racine du dépôt, vous pouvez lancer un serveur local :

```bash
python3 -m http.server 8000
```

Puis ouvrez la page HTML concernée à l'adresse `http://localhost:8000/html_advanced/`.

## Technologies

- HTML5
- CSS3 (variables personnalisées, typographie, couleurs et mise en page)