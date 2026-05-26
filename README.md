# Starbucks Landing Page

🔗 **Live Site:** [starbucks-landing-page](https://lukian2604.github.io/starbucks-landing-page)

## About

Starbucks Landing Page is a responsive landing page for a coffee brand. The design focuses on a dark aesthetic with green gradient accents and a clean modern layout — built entirely with HTML and SCSS/CSS, no frameworks.

## Sections

- **Header** — logo and navigation menu with anchor links
- **Hero** — title, description, CTA buttons, and statistics (users, customers, awards)
- **Benefits** — three-item list with icons (Tasty, Fast, Available)
- **Growth Statement** — lounge image, description, and bar chart graphic
- **New Products** — 4-card grid with cup image, title, price, and buy button
- **Events** — 5-card grid with background images, title, and more button
- **Contacts** — contact info, phone link, and store image
- **Footer** — logo, navigation lists, anchor links, and back-to-top button

## Tech Stack

| Technology | Details |
|------------|---------|
| HTML5 | Semantic markup |
| SCSS / CSS3 | Custom properties, Flexbox, Grid, BEM |
| Fonts | Montserrat Regular / Medium / SemiBold / ExtraBold — self-hosted `.woff2` |
| Icons | Custom SVG icons |
| Images | PNG / SVG assets |

## Project Structure

```
starbucks-landing-page/
├── index.html
├── fonts/
│   ├── Montserrat-Regular.woff2
│   ├── Montserrat-Medium.woff2
│   ├── Montserrat-SemiBold.woff2
│   └── Montserrat-ExtraBold.woff2
├── images/
│   ├── StarBucks-logo.png
│   ├── starbucks-website-icon.svg
│   ├── Cup/                       # 4 cup SVG images
│   ├── benefits/                  # 3 benefit icons + star
│   ├── Growth-statement/          # lounge + bar images
│   ├── events/                    # 5 event background images
│   ├── contacs/                   # contact image + tel icon
│   └── Elements/                  # background decorative SVGs
└── styles/
    ├── styles.scss
    ├── styles.css
    ├── _fonts.scss
    ├── _globals.scss
    ├── _variables.scss
    ├── _mixins.scss
    ├── _utils.scss
    ├── _media.scss
    ├── _normalize.scss
    └── blocks/
        ├── _header.scss
        ├── _hero.scss
        ├── _benefits.scss
        ├── _growth-statement.scss
        ├── _new-products.scss
        ├── _products.scss
        ├── _products-card.scss
        ├── _events.scss
        ├── _events-card.scss
        ├── _contacts.scss
        ├── _footer.scss
        └── _button.scss
```

## Getting Started

No build step required — open `index.html` directly in a browser or serve with any static file server:

```bash
# Using VS Code Live Server, or:
npx serve .
```

## Deployment

This project is deployed via GitHub Pages from the `main` branch root.

---

> **Disclaimer:** This project is for educational and portfolio purposes only. All Starbucks trademarks, logos, and brand assets belong to Starbucks Corporation.
