# Wallpaper Website (Wallora)

## Overview

Wallora is a responsive browsing site for 24 demo wallpapers.

## Purpose

Lets visitors browse, search and save favourite wallpapers for different screens.

## Features

- 24 wallpapers across 10 categories (Nature, Space, City, Cars, Animals, and more)
- Device filters (All, Desktop, Mobile, Tablet, 4K, HD) and live search
- Favourites saved in localStorage
- Preview modal with details
- Dark mode toggle
- Download button that opens the image (download count is a local demo counter, not real)

## Technologies

HTML, CSS, JavaScript, localStorage. No frameworks or build step; one self-contained `index.html`.

## Responsive Design

Layout adapts with CSS media queries. Tested without horizontal scrolling at 360, 390, 768, 1024 and 1440px widths.

## UI/UX

Image-led card grid, modal preview and persistent user preferences.

## Known Limitations

Images are hot-linked from Unsplash, so they need internet and could change or disappear. Check Unsplash licence/attribution before treating this as a public product.

## Project Structure

```text
03-wallpaper-website/
├── index.html
├── screenshots/
└── README.md
```

## Screenshots

_Screenshots to be added (take them from your live GitHub Pages URL)._

`screenshots/desktop-home.png` · `screenshots/mobile-home.png` · `screenshots/feature.png`

## Live Demo

[Live Demo](https://d-sandeepani.github.io/frontend-web-projects/ai-assisted-web-projects/03-wallpaper-website/)

## GitHub Repository

https://github.com/d-sandeepani/frontend-web-projects/tree/main/ai-assisted-web-projects/03-wallpaper-website

## AI-Assisted Development

This project was developed with AI-assisted support (ideation, coding assistance, debugging and development support). I reviewed, tested and adjusted the result. It is not described as 'built entirely by AI'.

## Learning Outcomes

Array/data-driven rendering, filtering and search, localStorage, modal and toast patterns.