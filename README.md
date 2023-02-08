# geOrchestra homepage

This repository is about providing development environment to build geOrchestra static pages, meant to be hosted in https://github.com/georchestra/htdocs

## Requirements

- nodeJs >= 16.0.0

## Quickstart

To start the home page in local dev environment:
```
npm install
npm run start
```

## Scripts

- `dev:home` run home page in dev mode
- `dev:header` run header in dev mode
- `build:home` builds home page and outputs it in your `dist/home` directory
- `build:header` builds header and outputs it in your `dist/header` directory
- `format` runs prettier format in write mode

## Deploy
To build an application, run `npm run build:{yourApp}`.
Copy the resources built in `./dist/{yourApp}` folder to your web server.

## Tech
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- prettier
- pre-commit hook (husky, lint-staged)
