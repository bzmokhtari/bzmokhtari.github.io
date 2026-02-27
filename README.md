# bzmokhtari.github.io

Personal portfolio website for **Behzad Mokhtari** — Firmware Integration Architect.

**Live:** [www.mokhtari.page](https://www.mokhtari.page)

## Tech Stack

- React 19 + TypeScript
- Tailwind CSS 4
- Vite (static build)
- GitHub Pages

## Sections

- **Hero** — Name, title, company trail, key stats
- **About** — Professional summary + CliftonStrengths profile
- **Experience** — Career timeline (TallTree, Ring, Roku, Samsung)
- **Skills** — Domains, technical skills, tools
- **Testimonials** — LinkedIn recommendations from colleagues
- **Contact** — CTA with LinkedIn, GitHub, Email links

## How to Extend

All content lives in `client/src/data/portfolio.ts`. To add or update:

1. Edit the data file — experience, skills, recommendations, etc.
2. Build: `npx vite build --config vite.ghpages.config.ts`
3. Copy `dist/ghpages/*` to this repo
4. Push to `main` branch

## License

MIT
