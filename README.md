# tank.ir Search — Nuxt

The classified-ads **search experience for tank.ir**, implemented with **Nuxt 2** — listing, filtering, ad detail pages, and a phone-number reveal interaction.

This repo is the Nuxt implementation of the same product; see also [`tank.ir-search-vue`](https://github.com/reihanyaghoobzade/tank.ir-search-vue) for the Vue 3 + Vite version. Building the same feature on both frameworks was a deliberate exercise in comparing routing, data fetching, and SSR trade-offs between Nuxt 2 and Vue 3 tooling.

## Pages

- `/` — search results with pagination
- `/_id` — ad detail page with seller info
- `/p` — static pages

## Getting Started

```bash
npm install
npm run dev        # http://localhost:3000
npm run build      # production build
npm run generate   # static site generation
```
