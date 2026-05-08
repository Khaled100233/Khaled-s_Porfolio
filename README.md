# Khaled Ehab Attia — Portfolio

Personal portfolio of an AI Engineer specializing in computer vision and LLM-powered systems.

**Live →** https://khaled100233.github.io/LaTex-CV/

## About

This is the source for my personal portfolio website. It showcases selected work across computer vision, deep learning, and LLM agent systems — including Therma Ear (a Vision Transformer for thermal-image diagnosis), Retail Analytics Copilot (a LangGraph + DSPy + RAG agent), and Robot Referee (real-time CV) — alongside my teaching work at GIU and AAST and my ongoing MSc in Data Science.

## Built with

Hand-written HTML, CSS, and a few small touches of vanilla JavaScript. No build step, no framework, no bundler — the site is just two files that GitHub Pages serves directly. Typography is set in Fraunces for display, Manrope for body, and JetBrains Mono for technical accents, all loaded from Google Fonts.

## Features

The site supports both dark and light themes, defaulting to your OS preference and remembering your choice in `localStorage` if you toggle. Layout is fully responsive down to mobile widths. A lightweight intersection observer reveals sections on scroll, and the hero animates in with a small staggered fade on first paint. Reduced-motion preferences are respected throughout.

## Structure

```
.
├── index.html      # markup + small inline scripts for theme + reveals
├── styles.css      # all styling; CSS variables drive both themes
└── README.md
```

All theme colors are defined at the top of `styles.css` under `:root[data-theme="dark"]` and `:root[data-theme="light"]` — change them there and the rest of the stylesheet picks up the new palette automatically.

## Running locally

Clone the repo and open `index.html` directly in any modern browser — there's nothing to install or build.

```bash
git clone https://github.com/Khaled100233/Khaled-Ehab-Portfolio.git
cd Khaled-Ehab-Portfolio
```

For a quick local server (useful if your browser is strict about loading fonts from `file://`):

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Contact

You can reach me by email at [kha.2002.ke@gmail.com](mailto:kha.2002.ke@gmail.com), on LinkedIn at [/in/khaled-ehab](https://linkedin.com/in/khaled-ehab), or on GitHub as [@Khaled100233](https://github.com/Khaled100233). I'm based in Cairo, Egypt.

---

© 2026 Khaled Ehab Attia
