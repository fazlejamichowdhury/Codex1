# Al Noor Mosque

Free, original two-page static mosque template: `index.html` and `visit.html`. No build step, CMS, paid libraries, backend, or account required. Original SVG artwork is included. Optional Google Fonts fall back to system fonts offline.

## Run locally

Use the existing checkout; each cloud task is already isolated. Do not create a Git worktree unless requested.

```sh
cd /workspace/Codex1
python3 -m http.server 8000 --bind 0.0.0.0
```

## Publish

Upload `index.html`, `visit.html`, `styles.css`, `script.js`, and `assets/` to any static host (for example Cloudflare Pages, Netlify, or GitHub Pages). Keep both HTML files at the same level. No environment variables or server functions are needed. Free host subdomains may be available; custom domain registration is separate.

## Webflow

These are portable HTML/CSS files, not a native Webflow Marketplace package. Webflow cannot directly import an entire HTML website. To publish in Webflow, recreate Home and Visit in the Designer, using this implementation as the visual reference. Use only two static pages and native sections, grids, buttons, and FAQ dropdowns; no CMS or paid embeds are needed. Upload the included SVG artwork to Assets. Recreate the CSS values as Webflow classes and use native mobile navigation. The free Starter site plan supports two pages on a webflow.io subdomain; confirm current plan terms. Publishing to a custom domain requires a paid Webflow site plan. No Webflow account was connected and no site has been published by this task.

## Before launch

- Replace the fictional Al Noor name and demonstration copy with approved mosque details.
- Replace example prayer times with an approved local timetable, including date range and timezone; do not present these samples as current times.
- Add verified address, opening hours, contact/booking details, class schedules, and accessibility information.
- Review visitor policies and translations with the mosque.
- This is independent of Lisbon Central Mosque. Its website could not be inspected because network policy blocked access. No affiliation or location-specific accuracy is claimed.

## License

Original code and SVG assets in this repository are MIT licensed (see LICENSE). Google Fonts are optional third-party resources under their respective font licenses.
