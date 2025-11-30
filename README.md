# Linux Distribution Guide

A fully responsive, image-driven website showcasing a massive collection of actively maintained Linux distributions — over **100 distros** — each with:

- Logo
- Description
- Desktop environment screenshot
- Quick links (Website / Documentation)
- Alternating section styling for readability

This project is meant to act as a visual Linux “field guide,” giving newcomers and enthusiasts a clean, attractive way to browse the modern Linux ecosystem.

---

## 🧩 Features

### ✔️ Over 100 Linux Distributions

Includes mainstream, niche, gaming-oriented, server-oriented, immutable, rolling-release, and mobile distributions.

### ✔️ Alternating Section Styles

Each distro switches between:

- `<section>`
- `<section class="section-two">`

This keeps the page readable and visually organized.

### ✔️ Desktop Screenshots for Every Distro

A consistent layout using a `.desktop` class (instead of repeated `id`), ensuring:

- Full-width screenshots
- Drop shadows
- Automatic responsiveness

### ✔️ Modern Dark UI

Color variables defined via CSS custom properties:

```css
:root {
  --dark-blue: #213347;
  --light-blue: #8fb0d6;
  --text: #a7b8c0;
  --lightest-blue: #00e5ff;
  --links: #7599c8;
}
```
