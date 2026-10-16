# care-manager-site

One-page landing page for Care Manager, a pre-launch iPhone app that helps adult children and siblings coordinate care for an aging parent. Plain HTML and CSS: `index.html`, `styles.css`, `favicon.svg`. No build step, no JavaScript, no analytics or cookies. The only external request is Google Fonts (Baloo 2 and Nunito).

## Preview locally

Open `index.html` in a browser, or run a small server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publish with GitHub Pages (later)

All paths are relative, so it works at `/care-manager-site/`. When ready: Settings, Pages, "Deploy from a branch", pick the branch (for example `main`) and the `/ (root)` folder.

## TODO before launch

1. **Pilot sign-up form (Formspree).** The form in `index.html` posts to the Formspree form `https://formspree.io/f/xnpjlwga`.
   - It uses plain HTML only (no Formspree JavaScript), a hidden honeypot field (`_gotcha`) and a subject line (`_subject`). Submissions appear in the Formspree dashboard.
2. **Fallback email.** `pilot@example.com` is a placeholder. Replace it with the real address everywhere it appears in `index.html` (search for `pilot@example.com`; there are TODO comments next to it).
