# Wave Loader

> A smooth animated wave loader made with 5 CSS bars and staggered `animation-delay` — pure HTML and CSS, zero JavaScript.

---

## Overview

A compact loading animation built with five `div` elements that scale up and down in a rhythmic wave pattern. The entire effect is driven by a single CSS `@keyframes` animation with staggered delays on each bar. Drop it into any project as a standalone loading indicator.

---

## How It Works

Five `.wave` divs inside a `.loader` container each run the same scale animation, offset by a small `animation-delay` increment — creating the rippling wave effect without any JavaScript.

```
Bar 1 → delay: 0s
Bar 2 → delay: 0.1s
Bar 3 → delay: 0.2s
Bar 4 → delay: 0.3s
Bar 5 → delay: 0.4s
```

---

## Usage

Copy the markup into your HTML:

```html
<div class="loader">
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
  <div class="wave"></div>
</div>
```

Link the stylesheet:

```html
<link rel="stylesheet" href="style.css">
```

---

## Customization

Tweak these values in `style.css` to adjust the look:

| Property | What it controls |
|----------|-----------------|
| `.wave` width / height | Bar dimensions |
| `.wave` background color | Bar color |
| `animation-duration` | Speed of the wave |
| `animation-delay` increments | Gap between each bar's bounce |
| `.loader` gap | Spacing between bars |

---

## Project Structure

```
wave_loader/
├── loading.html   # Minimal markup — 5 wave divs
└── style.css      # All animation logic lives here
```

---

## Related

Pair with [simplest_loader](https://github.com/illusionoftalha/simplest_loader) for a full-page preloader, or use this standalone as an inline loading indicator.

---

## License

© 2026 Sheikh Muhammad Talha Bin Khalid. All Rights Reserved.
