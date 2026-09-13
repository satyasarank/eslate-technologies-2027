# Cloudflare deployment

Cloudflare Workers Builds settings:
- Repository: `satyasarank/eslate-technologies-2027`
- Branch: `main`
- Root directory: empty
- Build command: `npm run build`
- Deploy command: `npx wrangler deploy`

The included `wrangler.jsonc` serves the Vite `dist` output and enables SPA fallback.
