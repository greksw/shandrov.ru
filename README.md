# shandrov.ru

Source repository for [shandrov.ru](https://shandrov.ru/) — Tudor Shandrov's technical portfolio and resume site focused on infrastructure engineering, Linux, virtualization, storage, monitoring, and networking.

## What the site contains

- technical portfolio and infrastructure project case studies;
- resume pages;
- Russian and English content;
- project pages covering production-oriented infrastructure work;
- privacy and supporting informational pages.

The site is intentionally kept separate from the individual tooling repositories in this GitHub profile. Those repositories contain focused examples of deployment, migration, backup, monitoring, and administration utilities; this site provides the higher-level professional context around them.

## Stack

- [Astro](https://astro.build/) 7;
- Node.js 24;
- static site generation;
- `@astrojs/sitemap`;
- Caddy deployment configuration under `infra/caddy/`.

## Local development

Use the Node.js version declared by `.nvmrc` / `package.json`.

```bash
npm ci
npm run dev
```

Create a production build:

```bash
npm run build
```

Preview the generated site locally:

```bash
npm run preview
```

## Repository structure

```text
.
├── src/          # Astro pages, layouts and components
├── public/       # static assets
├── infra/caddy/  # web-server/deployment configuration
├── astro.config.mjs
├── package.json
└── README.md
```

## Production site

https://shandrov.ru/

## Scope

This repository is the source for a personal technical portfolio, not a reusable website template or framework.

No open-source license has been selected for this repository.