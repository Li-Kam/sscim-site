# sscim-site

Parent studio website for **SSCIM** — home of [MoonKeep](moonkeep.html).

Plain static HTML/CSS, no build step.

## Pages

- `index.html` — studio home: hero, apps showcase, about, principles, contact
- `moonkeep.html` — MoonKeep product page
- `privacy.html` — privacy policy (MoonKeep)
- `support.html` — support / FAQ
- `styles.css` — shared design system

## Design system

Shares editorial DNA with MoonKeep (serif display, tracked small-caps labels,
warm restraint) but on its own palette:

- Surfaces: warm ink `#16120E` + parchment `#F3EDE0`
- Accent: burnished bronze `#C99860`
- MoonKeep's midnight-navy/gold (`#0A1230` / `#EBD3A2`) appears **only**
  inside the MoonKeep product card
- Type: Fraunces (display) + Inter (UI), via Google Fonts

## Develop

Open `index.html` directly, or:

```sh
python3 -m http.server 8080
```

## Deploy

Any static host (GitHub Pages, Cloudflare Pages, Netlify) — point it at the
repo root.
