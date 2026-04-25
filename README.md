# Chimeremeze Odinachi — Developer Portfolio

A clean, minimal, techy portfolio website built with semantic HTML5, CSS3, and vanilla JavaScript.

## Project Structure

```
yourname_portfolio/
├── index.html          ← Main HTML file
├── css/
│   └── styles.css      ← All styles (variables, layout, responsive)
├── images/
│   ├── profile.jpg     ← Hero section photo (replace with yours)
│   ├── about.jpg       ← About section photo (replace with yours)
│   ├── project1.jpg    ← Project 1 thumbnail
│   ├── project2.jpg    ← Project 2 thumbnail
│   ├── project3.jpg    ← Project 3 thumbnail
│   └── project4.jpg    ← Project 4 thumbnail
└── README.md
```

## Features

- **Sticky navigation** with active link highlighting and blur backdrop
- **Smooth scroll** to all sections via anchor links
- **Hamburger menu** on mobile with slide-in drawer
- **Scroll-reveal animations** on cards and sections
- **Responsive design** — mobile (320px), tablet (768px), desktop (1024px+)
- **CSS Grid & Flexbox** layouts throughout
- **Hover effects** on skill cards, project cards, and buttons
- **Dark techy theme** with terminal-inspired aesthetics

## How to Customise

1. **Replace images** — Drop your photos into `/images/` with the exact filenames listed above
2. **Update name** — Search/replace `Chimeremeze Odinachi` and `AM` throughout `index.html`
3. **Update content** — Edit the About paragraphs, skills list, project details, and contact info in `index.html`
4. **Change accent colour** — Edit `--accent` in the `:root` block of `styles.css`
5. **Swap fonts** — Change the Google Fonts import URL and update `--font-heading` / `--font-body` CSS variables

## Colour Palette

| Variable          | Value      | Usage              |
|-------------------|------------|--------------------|
| `--bg-primary`    | `#0b0e14`  | Page background    |
| `--bg-secondary`  | `#111620`  | Alternate sections |
| `--bg-card`       | `#161c28`  | Cards & inputs     |
| `--accent`        | `#00d4aa`  | Highlights & CTAs  |
| `--text-primary`  | `#e8edf5`  | Headings & body    |
| `--text-secondary`| `#8a99b3`  | Paragraphs         |

## Tech Stack

- HTML5 (semantic)
- CSS3 (custom properties, grid, flexbox, media queries)
- Vanilla JavaScript (Intersection Observer, smooth scroll, hamburger)
- [Font Awesome 6](https://fontawesome.com/) — icons
- [DevIcons](https://devicon.dev/) — tech/language icons
- [Google Fonts](https://fonts.google.com/) — Syne + Space Mono

## License

Free to use for personal portfolios. Please don't redistribute as a template.
