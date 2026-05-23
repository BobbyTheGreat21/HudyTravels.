# HUDY Travels

> Your Passport to Stress-Free Travel

A single-page landing site for **HUDY Travels**, a Maldives travel-curation service offering luxury resorts, local-island stays, and ocean excursions — every detail arranged by Hudha, the curator.

🔗 **Live site:** https://bobbythegreat21.github.io/HudyTravels./

## Tech stack

- **Static HTML** — one self-contained `index.html`, no build step
- **Tailwind CSS** via the Play CDN (`cdn.tailwindcss.com`)
- **Vanilla JavaScript** — mobile menu toggle + optional `localStorage` content overrides
- **Google Fonts** (Playfair Display + Montserrat) and **Font Awesome** for icons
- **WebP** images for fast loading

## Sections

| Section | Description |
|---|---|
| Hero | Headline and intro |
| The Maldives Collection | Three destination cards: Luxury Resorts, Local Islands, Excursions |
| Travel Services | Itinerary planning, resort/stay selection, curated excursions |
| Media Gallery | 12-image responsive grid |
| The Curator | About Hudha |
| Contact | Email, WhatsApp, Telegram, Instagram |

## Project structure

```
.
├── index.html                      # The entire site (markup, styles, scripts)
├── README.md
├── .gitignore
└── assets/
    ├── favicon.svg
    └── images/
        ├── destinations/           # luxury-resorts, local-islands, excursions (+ alt)
        ├── gallery/                # gallery-1 … gallery-12
        ├── about/                  # hudha-about-me
        └── brand/                  # hudy-travels logo
```

> Original full-resolution PNG/JPG sources live in a local `png/` folder, which is gitignored (the deployed site uses the lighter WebP versions — ~14 MB → ~1.4 MB).

## Running locally

No build or dependencies required. Either:

- Open `index.html` directly in a browser, **or**
- Serve the folder for a closer-to-production setup:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosted on **GitHub Pages**, served from the `main` branch. Pushing to `main` triggers an automatic redeploy.

## Contact

- ✉️ Email: hudytravels@gmail.com
- 💬 WhatsApp: [+960 765 6914](https://wa.me/9607656914)
- ✈️ Telegram: [@hudyzz](https://t.me/hudyzz)
- 📷 Instagram: [@hudytravels._](https://instagram.com/hudytravels._)

---

© 2026 HUDY Travels
