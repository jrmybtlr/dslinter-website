# DSLinter Website

Marketing site for [DSLinter](https://github.com/jrmybtlr/DSLinter), deployed to Cloudflare Workers.

## Development

```bash
pnpm install
pnpm dev
```

## Build

```bash
pnpm build
```

## Deploy

Requires [Wrangler](https://developers.cloudflare.com/workers/wrangler/) authenticated to your Cloudflare account:

```bash
pnpm deploy
```

Or push to `main` — GitHub Actions runs the deploy workflow when `CLOUDFLARE_API_TOKEN` is configured.
