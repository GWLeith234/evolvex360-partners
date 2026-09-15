# EvolveX360 Partners

Static partner landing pages served via GitHub Pages.

## Deploy

- Push to `main` = live on GitHub Pages.
- Custom domain: `partners.evolvex360.com` (see `CNAME`).
- Path pattern: `/<deck-slug>/` (example: `/icelandnow/`).

## Current decks

| Slug | Path |
|------|------|
| icelandnow | `/icelandnow/` |

## Local layout

```
/
  index.html          # hub
  CNAME               # partners.evolvex360.com
  icelandnow/         # IcelandNOW partner landing
    index.html
    landing.css
    assets/
    fonts/
    img/
    journey/
```

DNS for the custom domain is managed separately. Do not drop files on cPanel.
