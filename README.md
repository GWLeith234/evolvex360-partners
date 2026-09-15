# EvolveX360 Partners

Static partner landing pages served via GitHub Pages.

## Deploy

- Push to `main` = live on GitHub Pages.
- Custom domain: `partners.evolvex360.com` (held as `CNAME.HOLD-until-dns` until Abdul DNS is live).
- Path pattern: `/<deck-slug>/` (examples: `/icelandnow/`, `/wsl-yamaha/`).

## Current decks

| Slug | Path |
|------|------|
| icelandnow | `/icelandnow/` |
| wsl-yamaha | `/wsl-yamaha/` |

## Local layout

```
/
  index.html          # hub
  CNAME.HOLD-until-dns
  icelandnow/         # IcelandNOW partner landing
    index.html
    landing.css
    assets/
    fonts/
    img/
    journey/
  wsl-yamaha/         # WSL Sport Yamaha Summer Campaign
    index.html
    fonts/
    evx-logo-white.png
    preview-01.png
    preview-02.png
    WSL-Yamaha-Summer-Funnel-Jul-Aug-2026.pdf
```

DNS for the custom domain is managed separately. Do not drop files on cPanel. Do not enable the live `CNAME` until DNS is ready.
