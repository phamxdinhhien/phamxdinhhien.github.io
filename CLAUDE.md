# Hien Portfolio

Personal portfolio website for Pham Dinh Hien - Software Engineer.

## Tech Stack

- **Framework**: Astro (Static Site Generator)
- **Styling**: CSS with CSS Variables (Dark Theme)
- **Deployment**: GitHub Pages

## Development

```bash
npm install        # Install dependencies
npm run dev        # Start development server (localhost:4321)
npm run build      # Build for production
npm run preview    # Preview production build
```

## Project Structure

```
src/
├── components/    # Reusable Astro components
│   ├── Header.astro
│   ├── Hero.astro
│   ├── Skills.astro
│   ├── Experience.astro
│   ├── Education.astro
│   ├── Contact.astro
│   └── Footer.astro
├── layouts/       # Page layouts
│   └── Layout.astro
├── pages/         # Page routes
│   └── index.astro
└── styles/        # Global styles
    └── global.css
```

## Deployment

Push to `main` branch triggers automatic deployment via GitHub Actions.

Update `astro.config.mjs` with your GitHub username before deploying:
- `site`: Your GitHub Pages URL
- `base`: Your repository name

## Conventions

- Components use `.astro` extension
- CSS variables defined in `src/styles/global.css`
- Dark theme with accent color #06B6D4 (cyan)
