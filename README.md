# park13.digital

Static marketing site for **park13** (Park13 K.K.) — independent technical risk review.

## Structure

| Path | Locale |
|------|--------|
| `/` (`index.html`) | Japanese (primary) |
| `/en/` | English |
| `/assets/site.css` | Shared styles |
| `/assets/mark.svg` | Mark A logo |
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
