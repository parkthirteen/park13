# park13.digital

Single-page site for **park13** (park13株式会社) — software for modern finance. Specialist blockchain services are available through portfolio company [mini labo](https://mini-labo.org/).

## Structure

| Path | Locale |
|------|--------|
| `/` (`index.html`) | Japanese (primary) |
| `/en/` | English |
| `/assets/site.css` | Shared styles |
| `/assets/mark.svg` | Mark A logo (also inlined in each page so it adapts to dark mode) |
| `/assets/og.png` | Social preview image (1200×630) |
| `/assets/favicon.svg` | Favicon |
| `CNAME` | `park13.digital` |
| `robots.txt` / `sitemap.xml` | SEO |

No build step. GitHub Pages serves files as-is.

## Copy / brand sources (internal)

Vault: `biz/park13/brand/BRAND.md`, `SITE-COPY.md`. Offer: `biz/park13/consulting/`.

## Local preview

```bash
python3 -m http.server 8080
# open http://127.0.0.1:8080/ and /en/
```

## Contact

contact@park13.digital
