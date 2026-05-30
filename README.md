# Open Tables – Open Arms

Minimal, professional one-page website for **Open Tables – Open Arms**, a nonprofit food truck
serving homeless veterans, homeless communities, and impoverished neighborhoods.

Live domain: https://opentablesopenarms.org

## Stack

Plain static site — no build step, no framework.

```
index.html    # all page content
styles.css    # white / navy / gold theme
script.js     # mobile nav + footer year
assets/       # logo
```

## Run locally

Any static server works, e.g.:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Editing content

Search `index.html` for `PLACEHOLDER` to find the spots to fill in:

- **Founder story** and city/region served (About section)
- **Donate link** — replace the `href="#"` on the "Donate Now" button with your
  PayPal / GoFundMe / Givebutter / Zeffy URL
- **Contact email** — replace `hello@opentablesopenarms.org`
- **Social links** — replace the `#` hrefs in the Contact section footer

## Deploy

Static host of choice (Cloudflare Pages, Netlify, GitHub Pages). Point the Porkbun
domain `opentablesopenarms.org` at the host per its custom-domain instructions.
