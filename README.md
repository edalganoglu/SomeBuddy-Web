# SomeBuddy Web

Marketing site and legal pages for the SomeBuddy mobile app.

## Pages

| Path | Purpose |
|------|---------|
| `/` | Landing |
| `/privacy/` | Privacy Policy (App Store / Play) |
| `/terms/` | Terms of Use |
| `/support/` | Support contact |
| `/account-deletion/` | Account deletion (Apple requirement) |

## Deploy on Vercel

1. Import this repo in [Vercel](https://vercel.com/new)
2. Framework preset: **Other** (static)
3. Deploy — default URL: `somebuddy-web.vercel.app` (or rename project to `somebuddy`)
4. Optional: add custom domain `somebuddy.co` in Vercel → Domains

## Local preview

```bash
npx serve .
```

## App integration

Set in the mobile app `.env`:

```
EXPO_PUBLIC_WEB_BASE_URL=https://your-vercel-url.vercel.app
```

Legal links in the app read from this base URL.
