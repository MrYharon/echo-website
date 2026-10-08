# Echo Website

Official product website and live interactive laboratory for [Echo](https://github.com/MrYharon/Echo) &mdash; The AI Prompt Compiler.

## Overview

- **Live Compiler Laboratory**: In-browser client-side prompt compilation demonstration.
- **Kinetic Monogram**: Interactive 3D perspective tilt and opposing horizontal slab parallax matching the official Echo brand geometry.
- **Full-Bleed Acoustic Canvas**: Organic fluid acoustic ripple canvas reacting dynamically to cursor position and speed.
- **Zero Build Step**: Pure HTML5, CSS3, and modern vanilla JavaScript.

## Project Structure

```
├── index.html           # Main landing page & laboratory interface
├── style.css            # Stylesheet, typography, and responsive grid
├── script.js            # Kinetic acoustic canvas, 3D monogram parallax, and workbench logic
├── assets/
│   ├── brand-logo.png   # Official brand emblem (used for Open Graph & favicon)
│   └── echo-extension.zip # Packaged browser extension download
└── lib/
    ├── analyzer.js      # Prompt clarity scoring & noise detection engine
    └── architect.js     # Prompt contract compiler & guardrail synthesizer
```

## Running Locally

You can serve this repository using any static HTTP server:

```bash
# Using Python
python -m http.server 3000

# Using Node.js npx
npx serve .
```

Open `http://localhost:3000` in your web browser.

## Deployment

Because this repository contains static HTML/CSS/JS at the root level, it can be deployed with zero configuration on:
- **Vercel**: Import repository &rarr; Deploy (Framework Preset: Other)
- **Netlify**: Import repository &rarr; Publish directory: `.`
- **Cloudflare Pages**: Connect GitHub &rarr; Direct Upload / No build command
- **GitHub Pages**: Repository Settings &rarr; Pages &rarr; Source: Deploy from branch (`main` / root)
