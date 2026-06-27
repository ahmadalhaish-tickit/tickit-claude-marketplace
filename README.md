# TICKIT Claude Marketplace

Claude Code plugin marketplace from TICKIT.

## Register this marketplace

```bash
/plugin marketplace add ahmadalhaish-tickit/tickit-claude-marketplace
```

## Available plugins

### client-secret-exposure

Audits any project for secrets exposed in client-side code — web, Flutter, React Native, iOS, Android, backend.

```bash
/plugin install client-secret-exposure@tickit-claude-marketplace
```

Covers:
- Detection per platform: Next.js JS bundle, Flutter/React Native APK binary, iOS/Android binary, git history
- Classification: 15+ key types — safe vs dangerous vs partial
- Backend-for-Frontend (BFF) proxy pattern for any stack
- Environment variable best practices per platform
- Firebase App Check + Security Rules
- CORS vs server-side enforcement
- Post-fix checklist: rotate, remove, deploy, verify, clean history, restrict
