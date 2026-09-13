# Cloudflare Deployment

This project is configured for Cloudflare Workers Static Assets.

## Cloudflare settings

- Root directory: `eslate-technologies` (only if this is the directory containing this file in your GitHub repo)
- Build command: `npm run build`
- Deploy command: `npx wrangler deploy`
- Production branch: `main`

The Wrangler configuration serves the Vite build output from `dist` and enables SPA fallback routing.

## Important

Do not run `wrangler deploy` from a parent directory that does not contain `wrangler.jsonc`.
