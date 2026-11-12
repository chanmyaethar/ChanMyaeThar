# Chan Myae Thar Sasana Meditation Centre
A responsive Burmese and English website for Chan Myae Thar, with an elegant white, gold and burgundy visual identity and the centre's supplied emblem.

## Pages
- Home / `index.html`
- About / `about.html`
- Dhamma / `dhamma.html`
- Programs / `programs.html`
- Gallery / `gallery.html`
- Donations / `donate.html`
- Contact / `contact.html`
- Privacy / `privacy.html`

## Content management
Edit `data/site-config.js` to add approved contact information, actual programs, sermon media links, donation details and gallery entries. Content requiring verification is intentionally not invented.

## Deploy on Render
Create a Static Site in the Chan Myae Thar Render workspace and connect:
- Repository: `chanmyaethar/ChanMyaeThar`
- Branch: `main`
- Name: `chanmyaethar` (subject to availability)
- Build command: `echo 'Static website ready'`
- Publish directory: `.`
- Auto Deploy: enabled

`render.yaml` provides an optional blueprint. Confirm the assigned Render URL in Render Dashboard after a successful deploy; the preferred URL is not guaranteed until allocated.

## Capabilities and limitations
- Static HTML, CSS and vanilla JavaScript with no npm build dependencies.
- Myanmar/English language switch saved in browser localStorage.
- Mobile navigation, responsive layouts and basic SEO.
- A contact form opens a mail app once an official public email has been configured. It does not store or transmit messages to a server.
- No payment transactions are processed. Bank information appears only after verified details are configured.
- No fabricated retreat dates, teacher details, contact numbers, or bank accounts.
- The emblem was supplied by the site owner and optimized for fast loading.
- Advanced administration, payment processing and online receipts require additional backend services.

## Local preview
```sh
python3 -m http.server 8000
```
Open http://localhost:8000

Website prepared for Chan Myae Thar · Development: InnovateX.
