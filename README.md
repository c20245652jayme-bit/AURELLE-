# N/A — Network Administration

An informational network-administration website built with Astro.

## Requirements

- Node.js `>=22.23.4`
- npm

## Getting started

Run these commands from the project root:

```sh
npm install
npm run dev
```

Astro serves the site at `http://localhost:4321`.

## Available commands

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Build the static site into `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run astro -- --help` | Show Astro CLI commands |

## Project structure

```text
public/              Static assets served as-is
src/
  components/        Reusable UI components
  layouts/           Shared page layouts and document shell
  pages/             Route entry points (index.astro is `/`)
  sections/          Composed page sections
```

Place new routes in `src/pages/`. Keep shared UI in `src/components/`, page
shells in `src/layouts/`, and larger page sections in `src/sections/`.
