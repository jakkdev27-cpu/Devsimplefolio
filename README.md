# DevSimplefolio

[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?logo=github)](#)

Portfolio personnel de Kokou Jean Apôtre KPETSI, construit à partir du template Simplefolio et personnalisé avec un design moderne, sombre et premium.

<p align="center">
  <img src="src/assets/jakk-logo-1024.png" alt="Logo DevSimplefolio" width="220" />
</p>

## À propos

Ce projet est un portfolio one-page responsive conçu pour présenter mon profil, mes compétences, mes projets et mes réalisations dans le domaine du développement logiciel.

Il met en avant :

- une identité visuelle personnalisée,
- une navigation claire et fluide,
- des sections axées sur le profil professionnel,
- des cartes projets et liens vers les démonstrations / dépôts GitHub,
- un CV téléchargeable.

## Stack technique

- HTML5
- SCSS
- Bootstrap
- JavaScript
- Parcel
- ScrollReveal
- Vanilla Tilt

## Structure du projet

```bash
src/
├── index.html
├── styles.scss
├── assets/
├── data/
├── sass/
├── scripts/
├── index.js
└── ...
```

## Prérequis

- Node.js
- npm

## Installation

```bash
npm install
```

## Démarrage local

```bash
npm start
```

Puis ouvrir :

```bash
http://localhost:1234/
```

## Build de production

```bash
npm run build
```

## Assets

Les fichiers principaux sont dans le dossier `src/assets/` :

- `profile.png`
- `project1.png`
- `project2.png`
- `resume.pdf`
- `jakk-logo-1024.png`
- `jakk-icon-32.png`
- `jakk-icon-192.png`
- `jakk-icon-512.png`

## Personnalisation

Pour modifier le contenu du site :

- éditer `src/index.html`
- ajuster la palette dans `src/sass/abstracts/_variables.scss`
- modifier les styles dans `src/styles.scss` et les fichiers SCSS de `src/sass/`

## Licence et droits

Ce projet est dérivé du template Simplefolio et personnalisé pour un usage personnel/professionnel.

La licence MIT autorise la modification et la redistribution, sous réserve d’inclure les mentions de copyright et de licence. Pour cette raison, les crédits au template original sont conservés, et le portfolio a été adapté par Kokou Jean Apôtre KPETSI.

Le fichier de licence original est disponible dans le dépôt.

````

### (4) Contact Section

- On `<p>` tag with class name `.contact-wrapper__text`, include some custom call-to-action message.
- On `<a>` tag, put your email address on `href` property.

```html
<!-- **** Contact Section **** -->
<section id="contact">
  <div class="container">
    <h2 class="section-title">Contact</h2>
    <div class="contact-wrapper load-hidden">
      <p class="contact-wrapper__text">[Put your call to action here]</p>
      <a
        rel="noreferrer"
        target="_blank"
        class="cta-btn cta-btn--resume"
        href="mailto:example@email.com"
        >Call to Action</a
      >
    </div>
  </div>
</section>
<!-- /END Contact Section -->
````

### (5) Footer Section

- Put your Social Media URL on each `href` attribute of the `<a>` tags.
- If you an additional Social Media account different than Twitter, Linkedin or GitHub, then go to [Font Awesome Icons](https://fontawesome.com/v4.7.0/icons/) and search for the icon's class name you are looking.
- You can delete or add as many `<a>` tags your want.

```html
<footer class="footer navbar-static-bottom">
  ...
  <div class="social-links">
    <a href="#!" target="_blank">
      <i class="fa fa-twitter fa-inverse"></i>
    </a>
    <a href="#!" target="_blank">
      <i class="fa fa-linkedin fa-inverse"></i>
    </a>
    <a href="#!" target="_blank">
      <i class="fa fa-github fa-inverse"></i>
    </a>
  </div>
  ...
</footer>
```

### Step 2 - STYLES

Change the color theme of the website - (choose 2 colors to create a gradient)

Go to `/src/sass/abstracts/_variables.scss` and only change the values for this variables `$main-color` and `$secondary-color` with your prefered HEX color.
If you want to get some gradients inspiration I highly recommend you to check this website [UI Gradient](https://uigradients.com/#BrightVault)

```scss
// Default values
$main-color: #02aab0;
$secondary-color: #00cdac;
```

---

## Deployment 📦

Once you finish your setup. You need to put your website online!

I highly recommend to use [Netlify](https://netlify.com) because it is super easy.

## Technologies used 🛠️

- [Parcel](https://parceljs.org/) - Bundler
- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - Frontend component library
- [Sass](https://sass-lang.com/documentation) - CSS extension language
- [ScrollReveal.js](https://scrollrevealjs.org/) - JavaScript library
- [Tilt.js](https://gijsroge.github.io/tilt.js/) - JavaScript tiny parallax library

## Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/3a029bfd-575c-41e5-8249-c864d482c2e5/deploy-status)](https://app.netlify.com/sites/the-simplefolio/deploys)

## License 📄

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
