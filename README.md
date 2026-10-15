# Soha Sami — Research Portfolio

A responsive, multi-page portfolio built with Astro and designed for deployment on Vercel.

## Pages
- `/` — Home
- `/research/` — Research overview
- `/projects/` — GitHub projects
- `/articles/` — Blog and Substack writing
- `/resources/` — PDF and presentation library
- `/about/` — Background and contact links

## Requirements
- Node.js LTS (https://nodejs.org/)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Astro.

## Build check
```bash
npm run build
```
A successful build creates `dist/`.

## GitHub and Vercel
The repository root must contain `package.json`, `astro.config.mjs`, `vercel.json`, `src/`, and `public/`.
Import this repository into Vercel. Framework preset: Astro. Build command: `npm run build`. Output directory: `dist`. Root directory: `./` (the repository root).

## Before going live
Replace the placeholder LinkedIn URL in `src/layouts/BaseLayout.astro` and `src/pages/about.astro` with the correct profile URL. Check every external link and add only verified project results. The homepage's small chart is illustrative until replaced with a real research figure.
