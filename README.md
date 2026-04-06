# AIHub

An [Astro](https://astro.build) static website deployed to GitHub Pages via GitHub Actions.

## 🚀 Project Structure

```text
/
├── public/
│   └── favicon.svg
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |

## 🚢 Deployment

The site is automatically built and deployed to GitHub Pages whenever changes are pushed to the `main` branch, using the workflow defined in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).
