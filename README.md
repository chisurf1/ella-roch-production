# Ella Roch Production

Single-page stage management portfolio for **Ella Roch** (University of Michigan, Class of 2027).

## Files

- `index.html` — self-contained landing page (inline CSS + minimal JS; Google Fonts for Cormorant Garamond + DM Sans)
- `images/` — portfolio photos used on the page
  - `headshot.jpg` — professional portrait (About)
  - `stage-door.jpg` — STAGE DOOR portrait (About)
  - `act2-preset.jpg`, `flyrail-crew.jpg`, `set-stairs-crew.jpg`, `boat-crew.jpg` — Backstage gallery
- `Ella-Roch-SM-Resume.pdf` — one-page SM résumé (linked from Contact)

## Open locally

**Option A — double-click / open in browser**

```bash
open /workspace/ella-roch-production/index.html
```

On Linux you can also use `xdg-open`, or simply open the file from your file manager.

**Option B — local static server** (recommended for testing)

```bash
cd /workspace/ella-roch-production
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Host

Upload this folder (including `index.html`, `images/`, and the résumé PDF) to any static host:

- GitHub Pages / Cloudflare Pages / Netlify / Vercel — drop the folder or point the site root at this directory
- No build step, bundler, or Node required

## Contact / email

The live page links contact to Instagram only:

- [https://www.instagram.com/ellaroch.production/](https://www.instagram.com/ellaroch.production/)

No personal email or phone appears on the résumé or this site. To add email later:

1. Replace the “Request résumé” / contact note in `index.html` with a real `mailto:` address, **or**
2. Ask Douglas / Ella for the preferred address and wire it into the Contact section.

## Brand notes

- Dark stage / charcoal, warm amber–gold spotlight, cue-light red accents
- Credits use verified production titles only (no IG-only gallery shows as credits)
- Photos live in `images/`; About stacks headshot + stage-door; **Backstage** gallery uses production process shots with short captions only (no invented show titles or photo credits)
- Optional faculty mention in About: Jenn Rae Moore; Christianne Myers


## Contact on site
- Email: ellaroch@umich.edu
- Phone: +1 (269) 405-2321
- Instagram: @ellaroch.production
