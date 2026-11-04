# Demo photo assets

Generated with the built-in ImageGen tool for layout demos. These do not represent the maker's actual products.

| Photo | Saved asset |
| --- | --- |
| Existing utility knife | `assets/sample-knife.webp` |
| chef-walnut | `assets/sample-chef.webp` |
| field-charcoal | `assets/sample-field.webp` |
| workbench-wood | `assets/sample-workbench.webp` |
| handle-detail | `assets/sample-detail.webp` |

## Exact prompts for the four additional images

# Knife demo sample photo generation

Built-in image_gen, one call per asset, no retries or variants. All outputs are 1536 × 1024 PNG (3:2), illustrative placeholders and not real maker work. All four were visually inspected and accepted.

## chef-walnut.png

Use case: product-mockup
Asset type: illustrative sample photograph for a knife maker portfolio design demo, not documentation of real maker work.
Primary request: original photorealistic product photograph of one chef-style kitchen knife with a dark walnut handle, resting on pale linen and light natural stone.
Composition/framing: horizontal landscape 3:2 photograph; the entire knife, blade tip and handle included, comfortably inside frame. Calm, clean editorial product composition.
Lighting/mood: soft natural daylight, quiet craftsmanship mood.
Materials/textures: polished brushed steel blade, warm dark walnut grain, tactile off-white linen, subtle pale stone.
Constraints: one knife only; no logos, text, maker marks, watermark, people, hands, food, gore, action, or weapons use.

## field-charcoal.png

Use case: product-mockup
Asset type: illustrative sample photograph for a knife maker portfolio design demo, not documentation of real maker work.
Primary request: original photorealistic product photograph of one compact utility field knife with a charcoal micarta handle, resting on natural gray stone.
Composition/framing: horizontal landscape 3:2 photograph; the whole knife from blade tip to handle is visible, comfortably inside frame. Restrained outdoor product shot with simple stone background.
Lighting/mood: soft overcast daylight, calm neutral tones.
Materials/textures: charcoal micarta texture, brushed steel, natural gray stone.
Constraints: one knife only; no logos, text, maker marks, watermark, people, hands, animals, gore, action, or weapons use.

## workbench-wood.png

Use case: product-mockup
Asset type: illustrative sample photograph for a knife maker portfolio design demo, not documentation of real maker work.
Primary request: original photorealistic photograph of one small knife with a warm wood handle lying on a well-used wooden workbench.
Composition/framing: horizontal landscape 3:2 photograph; full knife from blade tip through handle comfortably visible. Quiet craft workshop editorial product photograph, minimal uncluttered scene.
Lighting/mood: soft windowlight, warm subdued tones.
Materials/textures: natural warm handle grain, brushed steel, worn workbench with subtle scratches and patina.
Constraints: one knife only; no logos, text, maker marks, watermark, people, hands, gore, action, or weapons use.

## handle-detail.png

Use case: product-mockup
Asset type: illustrative sample editorial detail photograph for a knife maker portfolio design demo, not documentation of real maker work.
Primary request: original photorealistic close-up editorial detail of a figured wood knife handle meeting a brushed steel bolster, on a plain gray background.
Composition/framing: horizontal landscape 3:2 photograph. Tight thoughtful crop emphasizes the figured wood grain, fit and finish, and metal transition. A small portion of blade may appear; handle and bolster dominate.
Lighting/mood: soft diffused daylight, quiet refined craftsmanship.
Materials/textures: expressive natural figured wood grain and subtle brushed steel texture.
Constraints: one knife detail only; no logos, text, maker marks, watermark, people, hands, gore, action, or weapons use.


## Additional sample product types

Built-in ImageGen outputs, used as illustrative product placeholders.

- Cleaver: `assets/sample-cleaver.webp`
- Folding pocket knife: `assets/sample-pocket.webp`

Exact prompts:

```json
{
  "mode": "built-in image_gen",
  "assets": [
    {
      "name": "cleaver",
      "prompt": "Use case: product-mockup\nAsset type: illustrative sample product photograph for a local knife maker portfolio demo, placeholder content only.\nPrimary request: a single broad rectangular chef/butcher cleaver with a satin stainless-steel blade and dark walnut handle.\nScene/backdrop: pale maple board on a simple light stone surface, clean uncluttered product setting.\nStyle/medium: realistic, professional product photography with believable metal and wood textures.\nComposition/framing: landscape 3:2 image, full cleaver visible from tip to end of handle with comfortable margin on every edge; near overhead three-quarter view; broad rectangular blade shape unmistakably visible.\nLighting/mood: soft natural side light, restrained gentle shadows, quiet refined craft portfolio mood.\nConstraints: only one knife, no text, no logos, no brand marks, no engraving, no watermark, no people or hands, no action, no food, no blood or gore. Blade and handle should be mechanically coherent. Do not crop the object."
    },
    {
      "name": "folding-pocket-knife",
      "prompt": "Use case: product-mockup\nAsset type: illustrative sample product photograph for a local knife maker portfolio demo, placeholder content only.\nPrimary request: a single open folding pocket knife, one compact satin stainless-steel blade with a pronounced drop-point shape and a dark brown-charcoal handle, visible pivot and folding mechanism.\nScene/backdrop: simple blue-gray woven fabric on a neutral tabletop, uncluttered product setting.\nStyle/medium: realistic, professional product photography with believable satin metal and handle textures.\nComposition/framing: landscape 3:2 image, the full open folding pocket knife visible with comfortable margin on every edge; near overhead three-quarter view; blade extends from handle in a plausible open position; pivot clearly visible; compact folding-knife proportions unmistakable.\nLighting/mood: soft daylight, controlled highlights and gentle shadows, quiet refined craft portfolio mood.\nConstraints: only one knife, only one blade, no text, no logos, no brand marks, no engraving, no watermark, no people or hands, no action, no food, no blood or gore. Knife geometry and folding mechanism must be mechanically coherent. Do not crop the object."
    }
  ]
}

```


## Old Forge landscape — style 03

Generated with built-in ImageGen, one call, no retries. Original output: 1859 × 846 PNG. Visually inspected and converted to `assets/old-forge-landscape.webp` (quality 88) for the site. This is original illustrative fantasy artwork, not a photograph of the maker’s workshop.

Saved original: `/private/tmp/knife-fantasy-landscape/old-forge-landscape.png`

Exact prompt:

```text
Use case: illustration-story
Asset type: traditional fantasy landscape illustration for an artisan knifemaker portfolio website hero
Primary request: An original, timeless high-fantasy landscape, evocative of old illustrated epic fantasy books: an ancient misty forest, distant jagged mountains, a quiet winding river, and a small old stone forge or workshop nestled at the forest edge with one warm amber window. The workshop is a modest place of craftsmanship within a vast natural world.
Style/medium: Hand-painted traditional gouache and oil painting, subtle paper and brush textures, richly observed natural scenery, mature and believable, an illustrated book frontispiece.
Composition/framing: Wide panoramic landscape approximately 2.2:1. A beautiful layered valley view, tree trunks and foliage framing the edges, river leading the eye toward distant peaks, small stone forge at the forest edge in the middle distance. Keep the important subject matter in the horizontal middle band so the image can be cropped modestly to a wide website banner. No space reserved for text; website text will appear below the illustration.
Lighting/mood: Quiet golden-hour light through cool forest mist, luminous distant air, warm amber craftshop glow, contemplative, storied, welcoming.
Color palette: Subdued fir green, slate blue, ochre and warm gold; harmonious natural pigments, deep shaded greens and softly luminous sky.
Constraints: Original setting only. No text, lettering, logos, watermark, recognizable fantasy characters or buildings, or modern objects. No game UI, no glossy 3D, no photorealism, no neon, no weapons displayed in landscape.
```
