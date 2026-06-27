# TICKIT Claude Marketplace

Claude Code plugin marketplace from TICKIT.

## Register this marketplace

```bash
/plugin marketplace add ahmadalhaish-tickit/tickit-claude-marketplace
```

## Available plugins

### nextjs-secret-exposure

Audits Next.js apps for secrets exposed in the client-side JS bundle.

```bash
/plugin install nextjs-secret-exposure@tickit-claude-marketplace
```

Covers:
- Detecting `NEXT_PUBLIC_` variables baked into the bundle
- Classification: dangerous vs public by design
- Server-side proxy fix patterns for Google Maps, payment credentials
- Firebase App Check vs CORS
- Post-fix verification checklist for Vercel
