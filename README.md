# Good Health Care Lab — Website

Static one-page site for Good Health Care Lab, Kumarikata, Tamulpur.

## Files
- `index.html` — all page content
- `styles.css` — design/styling
- `script.js` — mobile menu + footer year

## Before you go live — replace these placeholders
Search the files for these and update:
- `+910000000000` / `+91-00000-00000` — replace with the real WhatsApp number and phone number (all occurrences, in `index.html`)
- Doctor names, specialty, and chamber timings — in the "Doctors" section of `index.html`
- Opening hours — in the "Contact" section
- Services/test list — edit the `<ul class="services-list">` items to match the lab's actual test menu

## Adding real photos
Create an `images/` folder, drop photos in (e.g. `images/lab-front.jpg`, `images/doctor1.jpg`), then reference them in `index.html`, e.g.:
```html
<img src="images/doctor1.jpg" alt="Dr. Name">
```
This can replace the emoji placeholders in the doctor cards and facility icons.

## Deploying on GitHub Pages
1. Create a new GitHub repository (e.g. `good-health-care-lab`).
2. Upload `index.html`, `styles.css`, `script.js` (and an `images/` folder if used) to the repo root.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/root`.
5. Save — GitHub will give a live URL like `https://<username>.github.io/good-health-care-lab/` within a few minutes.

## Later, if needed
- Custom domain: buy a domain and add it under Settings → Pages → Custom domain.
- Reports download / patient login: was intentionally left out for now — will need a small backend (e.g. Firebase) when you're ready for it.
