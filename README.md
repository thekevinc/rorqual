# rorqual

Landing page for [rorqual.xyz](https://rorqual.xyz) — a hub for finance / market tools.

## Stack

- [Astro](https://astro.build) (static, zero-JS by default)
- Vanilla CSS, scoped per component
- Deployed via Cloudflare Pages

## Develop

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # build to dist/
npm run preview  # serve dist/ locally
```

## Deploy (Cloudflare Pages)

1. Push to GitHub
2. Cloudflare dashboard → Pages → Create → Connect to Git → pick this repo
3. Build command: `npm run build`
4. Build output: `dist`
5. Add custom domain `rorqual.xyz`
