# Mama Njeri's Kitchen

A small, responsive practice website for a fictional Kenyan restaurant,
**Mama Njeri's Kitchen**, built with semantic HTML and modern CSS.

## Live project

Once GitHub Pages is enabled, this project will be available at:

https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/

## What it demonstrates

- **Mobile-first responsive layout** — base styles are written for small
  screens first, with progressive enhancements at wider breakpoints.
- **CSS Grid template areas** — the page uses named grid areas to arrange
  the header, main content, sidebar, and footer. On phones, these areas
  stack vertically; from `64rem`, the main content sits beside the sidebar.
- **Safe `auto-fit` grid pattern** — the menu and food gallery use
  `repeat(auto-fit, minmax(min(16rem, 100%), 1fr))` and
  `repeat(auto-fit, minmax(min(10rem, 100%), 1fr))`, allowing columns to
  respond naturally without fixed-column media queries.
- **Flexbox components** — Flexbox is used for smaller component layouts,
  including the navigation, hero actions, menu-card footers, and about
  section.
- **Grid alignment** — the project includes examples of `align-self`,
  `place-items`, and `justify-content`.
- **Accessible form markup** — the contact form uses associated labels,
  semantic inputs, required fields, and visible focus styles.

## Project structure

```text
.
├── index.html
├── styles.css
└── images/
```

## How to view locally

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Resize the browser window from about 360 px to full width to see the
   responsive grid behaviour.

## Technologies used

- HTML5
- CSS Grid
- Flexbox
- Google Fonts

## Purpose

This is a practice project for learning responsive web design and modern
CSS layout techniques. It is intended as a small, complete portfolio
project demonstrating practical front-end skills.
