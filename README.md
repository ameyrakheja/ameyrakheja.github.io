# Knife portfolio — style demos

Five static, local design directions for a knife-maker portfolio. Each uses the same placeholder name, contact address, lorem ipsum copy, and five illustrative knife product photographs, with a shared header for switching styles. No installation or build step is needed.

| Page | Direction |
| --- | --- |
| `index.html` | Contact Sheet — minimal photographer portfolio |
| `field.html` | Field Issue — practical gear catalog |
| `zine.html` | Old Forge — traditional fantasy, painted landscape, forest green and parchment |
| `object.html` | Object Study — quiet museum gallery |
| `ledger.html` | Workshop Ledger — architectural split layout |

## Preview

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open <http://127.0.0.1:4173/> and use the header to compare all five pages. Links work without JavaScript and can be bookmarked separately.

## Placeholder content

- Replace `Your Name`, `Knife name`, and `hello@example.com` in each HTML page once the actual details are available. The email links currently use a reserved example address.
- The `assets/sample-*.webp` images are AI-generated illustrative artwork, not the maker's real work. Keep the disclosure until it is replaced with real photography, then update the captions and image alt text.
- `styles.css` contains the shared demo switcher and five separately scoped page styles.
- `assets/favicon.svg` contains the placeholder initials.

## Review and hosting

The current design exploration stays local. Show the previews before opening or updating pull requests or publishing. Choose a direction before turning it into the final site.

The existing `CNAME` (`amey.zip`) and `.nojekyll` remain unchanged. The repository's Pages setup publishes `main`; the local demos do not change the live site until explicitly published through the agreed review workflow.

Photo asset paths and the exact generation prompts are recorded in `assets/image-prompts.md`.

## Sample product groups

The three category links jump to Field knives (Camp knife and Field knife), Kitchen knives (Chef’s knife and Cleaver), and Pocket knives (Folding knife). Each style shows five example products with lorem ipsum descriptions and product-specific email inquiry links. These are illustrative placeholders, not real inventory. Older unused sample photos remain available in assets for design exploration.
