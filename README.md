# jollyjoker992.github.io

Personal site of Hieu Pham, published at <https://jollyjoker992.github.io/>.

Plain HTML and CSS: no framework, no build step, no JavaScript, no tracking.

| File | What |
|---|---|
| `index.html` | The page, with Open Graph tags and schema.org `Person` data |
| `assets/style.css` | Styles; light and dark follow the system setting |
| `assets/img/og.png` | 1200×630 link preview image |
| `404.html`, `robots.txt`, `sitemap.xml`, `favicon.svg` | The usual site files |
| `.github/workflows/pages.yml` | Validates HTML and links on every push and PR, deploys `main` to Pages |

## Edit and preview

```sh
python3 -m http.server 8000   # open http://localhost:8000
```

Push to `main` and the workflow deploys it. One-time setup: **Settings → Pages → Source: GitHub Actions**.
