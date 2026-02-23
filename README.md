# GamePedia

L'encyclopédie en ligne dédiée aux jeux vidéo.

## Description

GamePedia est un mini-wiki gaming qui regroupe des fiches complètes sur les plus grands titres du jeu vidéo. Le site propose un classement communautaire, des pages détaillées par jeu, un formulaire de contact et une newsletter.

## Pages

| Page           | Description                                                                                 |
| -------------- | ------------------------------------------------------------------------------------------- |
| `index.html`   | Page d'accueil — catégories, classement des meilleurs jeux (tableau comparatif), newsletter |
| `zelda.html`   | Fiche dédiée à _The Legend of Zelda: Tears of the Kingdom_                                  |
| `baldur.html`  | Fiche dédiée à _Baldur's Gate 3_                                                            |
| `elden.html`   | Fiche dédiée à _Elden Ring_                                                                 |
| `contact.html` | Formulaire de contact avec champs structurés et infos de contact                            |

## Structure du Projet

```
game_pedia/
├── images/
│   ├── logo-gamepedia.svg
│   ├── zelda-cover.jpg
│   ├── baldur_gate.jpg
│   └── elden-ring.avif
├── audio/
│   ├── zelda-theme.mp3
│   ├── baldur.mp3
│   └── elden-theme.mp3
├── index.html
├── zelda.html
├── baldur.html
├── elden.html
├── contact.html
└── README.md
```

## Concepts HTML Appliqués

- Structure sémantique (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- Texte sémantique (`<em>`, `<strong>`, `<h1>`–`<h3>`, `<abbr>`, `<time>`)
- Navigation multi-pages cohérente avec `aria-current="page"`
- Navigation locale (`<nav aria-label="Sommaire de la page">`)
- Skip link pour l'accessibilité
- Liens externes sécurisés (`target="_blank"`, `rel="noopener noreferrer"`)
- Images avec `alt` descriptifs, `width`, `height`, `loading="lazy"`
- Figures avec légendes (`<figure>`, `<figcaption>`)
- Tableaux accessibles (`<caption>`, `<thead>`, `<tbody>`, `scope`)
- Formulaires structurés (`<fieldset>`, `<legend>`, `<select>`, `<textarea>`, `required`)
- Multimédia (`<iframe>` YouTube, `<audio>` avec fallback)
- SEO (`<title>`, `<meta description>`, Open Graph)
- Favicon sur toutes les pages
- Performance (`loading="lazy"`, `width`/`height`, ordre du `<head>` optimisé)
- `<meter>` pour les notes Metacritic
- `lang="en"` sur les termes anglais
- `<address>` pour les infos de contact
- Validé W3C (0 erreurs)

## Contexte

Projet Fil Rouge A réalisé dans le cadre d'une formation HTML pure.
Ce projet a évolué au fil des 16 modules pour intégrer progressivement toutes les notions étudiées.

## Auteur

Réalisé par **Moaye Kelly**.
