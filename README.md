# German with Brezi — website

Public website for **German with Brezi**: online German A1 and A2 classes for beginners in India, taught by Sruthi.

Live at **https://germanwithbrezi.github.io** (GitHub Pages, served from the `main` branch root).

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page: hero, courses, level quiz, batches, FAQ, starter kit, demo booking |
| `play.html` | Play & learn: grammar comic, der/die/das game, flip cards |
| `assets/sruthi.jpg` | Teacher photo |
| `assets/petite-vue.iife.js` | Small library that powers the interactive parts (no build step needed) |

Edit the HTML directly and push to `main`; the site updates within a minute or two.

## Placeholders still to fill

Search for `[` in `index.html`: `[START DATE]`, `[DATE]`, `[GOOGLE FORM LINK]`, `[CALENDLY LINK]`, `[STARTER KIT FORM LINK]`, `[INSTAGRAM LINK]`, `[@HANDLE]`, student reviews.

## Custom domain (later)

1. Buy the domain (e.g. germanwithbrezi.in).
2. Repo **Settings → Pages → Custom domain** → enter it.
3. At the domain seller, add A records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` and a `www` CNAME to `germanwithbrezi.github.io`.
4. Tick **Enforce HTTPS** once it appears.
