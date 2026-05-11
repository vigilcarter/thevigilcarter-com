# thevigilcarter.com

Source for [thevigilcarter.com](https://thevigilcarter.com). Personal site of Vigil Carter.

## Structure

```
site/                            production source
  index.html                     home — writing list + about link
  about/index.html               one paragraph
  letting-the-show-work/         essay 1
  the-mirror/                    essay 2
  styles.css                     shared styles
  favicon.svg
  vercel.json                    hosting config
  robots.txt
  sitemap.xml

drafts/                          essay markdown sources
```

## Local preview

```
cd site
python -m http.server 8000
```

Open http://localhost:8000.

## Deploy

Hosted on Vercel from this GitHub repo. Domain `thevigilcarter.com` points at Vercel via apex `A` record and `www` `CNAME` in GoDaddy.

To deploy a change:

```
git add .
git commit -m "describe the change"
git push
```

Vercel auto-deploys from `main`.

## Voice and style

- Source Serif 4 throughout. No sans-serif anywhere.
- Palette: warm dark (`#0e0a08`), cream text (`#f0e6d6`), burnt amber accent (`#c98140`).
- No em-dashes. The rule is hard.
- Editorial register. Reading-first layout. No nav menu, no footer beyond the wordmark, no animation beyond a quiet entrance fade.

## Contact

`vigil@thevigilcarter.com` (email forwarding to be set up via GoDaddy or Microsoft 365 once domain is live).
