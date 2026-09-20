# savitha.us v2

Clean, static Vite website for Savitha Rameshkumar. It has no backend dependency and no Wrangler deploy step.

## Cloudflare Pages settings

- Framework preset: `Vite`
- Build command: `pnpm build`
- Build output directory: `dist`
- Deploy command: **leave blank**
- Root directory: repository root

After pushing this folder to a new GitHub repository, connect that repository to a new Cloudflare Pages project. Cloudflare will build and publish `dist` automatically.

## Local preview

```bash
npm install
npm run dev
```

The contact experience is deliberately transparent: calls and emails use standard `tel:` and `mailto:` links. Add a form service or a server-side endpoint only when you have the required credentials.
