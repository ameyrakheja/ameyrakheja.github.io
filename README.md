# Knife maker portfolio

A minimal knife portfolio: a name, one photograph, its caption, and an email link. It uses plain HTML and CSS, with no installation, build process, JavaScript runtime, or database.

## Preview locally

From the repository folder:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open <http://127.0.0.1:4173>.

## Replace the placeholders

1. In `index.html`, replace `Your Name`, the page title and description, `Knife name`.
2. Replace both occurrences of `hello@example.com`, including the address in the `mailto:` link. The link opens the visitor's email app; there is no contact-form backend.
3. Replace `assets/sample-knife.webp` with a real product photograph. Update the image source, alternative text, caption, and dimensions when replacing it.
4. Update the `YN` initials in `assets/favicon.svg`.
5. Remove the AI-generated photo label once it has been replaced with real photography.

The supplied image is AI-generated placeholder artwork. Do not describe it as the maker's actual work or inventory.

## Development and publishing

- Create a branch, make changes, preview locally, and open a pull request against `main`.
- The existing GitHub Pages configuration publishes the root of `main`. Merging an approved pull request triggers its normal deployment.
- `.nojekyll` tells GitHub Pages to serve the static files directly. No custom Actions workflow or hosting migration is required.
- The existing `CNAME` is preserved. Manage the domain and HTTPS through the repository's Pages settings.
- `AGENTS.md` gives Codex durable project context. Ask Codex to update the page, check it locally, and prepare a pull request.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Name, photograph, caption, and inquiry email link |
| `styles.css` | Layout, typography, colors, and responsive styles |
| `assets/sample-knife.webp` | Clearly labeled sample image |
| `assets/favicon.svg` | Placeholder brand initials |
| `CNAME` | Existing custom domain |
