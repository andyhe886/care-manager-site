# care-manager-site

One-page landing page for Care Manager, a pre-launch iPhone app that helps adult children and siblings coordinate care for an aging parent. Plain HTML and CSS: `index.html`, `styles.css`, `favicon.svg`. No build step, no JavaScript, no analytics or cookies. The only external request is Google Fonts (Baloo 2 and Nunito).

## Preview locally

Open `index.html` in a browser, or run a small server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publishing

All paths are relative, so it works at `/care-manager-site/`. Published by GitHub Pages from `main` (root) at https://andyhe886.github.io/care-manager-site/.

## Pilot sign-up form

The form in `index.html` posts to the Formspree form `https://formspree.io/f/xnpjlwga`.
It uses plain HTML only (no Formspree JavaScript), a hidden honeypot field (`_gotcha`) and a subject line (`_subject`). Submissions appear in the Formspree dashboard.
