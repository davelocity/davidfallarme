# davidfallarme

Personal site for David Fallarme: a static one-pager at [davidfallarme.com](https://davidfallarme.com/).

## Stack

- [Astro](https://astro.build) static build
- Instrument Sans for the heading, Source Serif 4 for body copy
- Deployed to Cloudflare Pages (`davidfallarme`)

## Local

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Output is `dist/`. Cloudflare Pages should use:

- **Project name:** `davidfallarme`
- **Build command:** `npm run build`
- **Output directory:** `dist`
- **Production URL:** https://davidfallarme.com/
