# Ansh Verma — Frontend Developer Portfolio

> Clean code. Sharp design. Real results.

A personal portfolio website built from scratch — fast, responsive, and pixel-perfect across all devices.

---

## 🌐 Live Preview

Deploy this file on any static host (GitHub Pages, Netlify, Vercel) to get it live instantly.

---

## ✨ Features

- **Dark / Light mode** — toggleable theme with smooth transitions, persisted via localStorage
- **Animated hero section** — floating orbs, dot grid background, and staggered entrance animations
- **Projects showcase** — featured project with expandable backend details panel and tabbed architecture breakdown
- **Skills grid** — categorized by Frontend, Backend, Tools, and Design
- **Contact section** — email, phone, and GitHub links with a CTA card
- **Responsive design** — mobile-first with hamburger nav and full-screen overlay menu
- **Scroll reveal** — elements animate in as you scroll using IntersectionObserver
- **Active nav highlighting** — nav links update as you scroll through sections

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Fonts | Syne, DM Sans, JetBrains Mono (Google Fonts) |
| Icons | Font Awesome 6.5 |
| Scripting | Vanilla JavaScript (no frameworks) |

---

## 📁 Structure

This is a **single-file portfolio** — all HTML, CSS, and JavaScript live in one `.html` file for maximum portability and simplicity.

```
portfolio.html
├── <head>         — Meta tags, fonts, styles
├── <nav>          — Fixed navbar + mobile overlay menu
├── #hero          — Intro, stats, animated code card
├── #about         — Bio, highlight cards
├── #projects      — Featured project + project grid
├── #skills        — Skills grouped by category
├── #contact       — Contact info + CTA box
└── <footer>       — Links and copyright
```

---

## 🚀 Getting Started

No build tools or dependencies needed. Just open the file:

```bash
# Clone or download the file, then:
open portfolio.html
```

Or drag and drop `portfolio.html` into any browser.

---

## 🎨 Customization

All design tokens are CSS custom properties in `:root` — easy to restyle:

```css
:root {
  --accent: #BAFF39;        /* Primary accent color */
  --font-h: 'Syne';         /* Heading font */
  --font-b: 'DM Sans';      /* Body font */
  --font-m: 'JetBrains Mono'; /* Monospace font */
}
```

To update content, search for these sections in the HTML:
- **Name / title** → `<title>` tag and `<h1>` in hero
- **Bio** → `#about` section
- **Projects** → `.proj-feat` and `.proj-card` blocks
- **Contact info** → `#contact` section (email, phone, GitHub)

---

## 📬 Contact

**Ansh Verma**
- 📧 Email: [anshverma@email.com]
- 📞 Phone: +91 9555918524
- 🐙 GitHub: [github.com/anshv9084-byte](https://github.com/anshv9084-byte)

---

## 📄 License

Built and designed from scratch by Ansh Verma © 2026. Feel free to use as inspiration — a credit is appreciated!
