# Portofolio — Personal Portfolio Site

Personal portfolio site for **Andhika Andriana Putra** — a student developer showcasing selected work, skills, and contact pathways.

Built as a fast, motion-driven Next.js application. The site emphasizes a single, focused narrative: a hero, features, a portfolio grid, pricing reference, and FAQ, all wrapping into a single WhatsApp / contact conversion.

**Live**: https://portofolio-kappa-sooty.vercel.app

## Stack

- **Next.js 16** (App Router) on **React 19**
- **Tailwind CSS v4** + PostCSS
- **Motion** + **Framer Motion** for component and scroll animations
- **Three.js** / **@react-three/fiber** / **@react-three/drei** for 3D accents
- **OGL** + **meshline** for WebGL line effects
- **ESLint** with `eslint-config-next`
- **React Compiler** enabled via `babel-plugin-react-compiler`

## Routes

| Path | Description |
| --- | --- |
| `/` | Hero + features + portfolio + FAQ + CTA |
| `/harga` | Pricing reference |
| `/keuntungan` | Why work with me |
| `/portofolio` | Case-study grid |
| `/maintenance` | Maintenance / retainer plans |
| `/sitemap.xml` | Dynamic sitemap route |
| `/robots.txt` | Dynamic robots route |

## Project structure

```
src/
  app/
    layout.js
    page.js
    harga/         page.js
    keuntungan/    page.js
    portofolio/    page.js
    maintenance/   page.js
    robots.txt/    route.ts
    sitemap.xml/   route.ts
    globals.css
  components/      Hero, Navbar, Footer, Features, FAQ, CursorGlow, DeviceMockup, ...
  lib/             utilities
public/            static assets
```

## Local development

```bash
npm install
npm run dev          # http://localhost:3000
```

Other scripts:

```bash
npm run build
npm run start
npm run lint
```

## Design notes

- Single-page storytelling with a dark, neon-accented palette
- Intro loader + custom cursor glow for the first paint
- 3D device mockups rendered with React Three Fiber
- Fully responsive (mobile-first)

## License

All rights reserved. Source code is published for portfolio purposes; please contact the author before reuse.
