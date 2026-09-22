# Signal & State

An original gallery of 110 fully-working interaction design studies,  spanning fintech, food, health, travel, and more. Every study is live: click a card and it runs, not just describes itself.

**View:** https://signal-and-state.vercel.app/
<img width="1042" height="680" alt="image" src="https://github.com/user-attachments/assets/fecd039b-646e-4980-a233-1880abbfe5a7" />


Designed and built by [Shouvick Koley](https://shouvick.design).

## About

This is a single self-contained static page — no framework, no build step, no dependencies beyond one Google Fonts stylesheet. All layout, styling, and the 33 shared interaction engines that power the 110 studies are inline in `index.html`.

## Local preview

Just open the file directly, or serve it with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```

## Deploying

### Vercel

This repo needs zero configuration — Vercel auto-detects a static `index.html` at the root.

**Via the dashboard:** go to [vercel.com/new](https://vercel.com/new), import this repository, and click Deploy.

**Via the CLI:**

```bash
npm i -g vercel
vercel        # first deploy, follow the prompts
vercel --prod # promote to production
```

### Anywhere else

It's a static file, so it will also deploy as-is to Netlify, GitHub Pages, Cloudflare Pages, or any static host — just point the host at `index.html`.

## Credits

Design, copy, and all 33 interaction engines by Shouvick Koley ([shouvick.design](https://shouvick.design) · [sk@shouvick.design](mailto:sk@shouvick.design)).
