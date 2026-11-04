# Knife maker portfolio

- This is a single-page knife portfolio with commission inquiries, not an ecommerce site. Do not add honey, checkout, payment processing, accounts, or a database.
- Keep the site static and dependency-free unless a requested feature warrants a framework. `index.html`, `field.html`, `zine.html`, `object.html`, and `ledger.html` own the five demo layouts; `styles.css` owns presentation; `assets/` owns images and the favicon.
- Branding, product descriptions, and `hello@example.com` are intentional placeholders. The sample knife image is AI-generated and must remain identified as illustrative until replaced with real product photography.
- Preserve `CNAME` and the existing GitHub Pages deployment settings. `.nojekyll` allows Pages to serve these files directly.
- Work on a branch and open a pull request for review. The current Pages setup publishes `main` after merging; do not push changes directly to `main` unless requested.
- Before handoff, check local links and assets, mobile and desktop layout, keyboard navigation, and any changed interaction. A local preview can run with `python3 -m http.server 4173 --bind 127.0.0.1`.

- Current design exploration is local only. Show previews here before creating or updating pull requests or publishing. The shared header switches between the five style pages; keep it consistent and mark the active page with `aria-current="page"`.
