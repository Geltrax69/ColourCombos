# ColourCombos

Colour palettes extracted from reference poster images. Each combo keeps the
colors **in the order they appear in the image's swatch column** (top to
bottom), plus notes on how each color is used in the poster.

`combos.json` is the source of truth — import it directly into the webpage
later (fetch, or `import combos from './combos.json'` with a bundler).

> Hex values were sampled from the swatch blocks in the reference images
> (mean pixel color), so they are screen/web approximations, not official
> Pantone values. Pantone labels were transcribed from the image labels.

## 1. Fresh Lemons — blue → red → yellow

| # | Color | Pantone | Hex | Used for |
|---|-------|---------|-----|----------|
| 1 | Deep Blue | P 105-8 C | `#25366c` | Poster background |
| 2 | Lemon Red | P 48-8 C | `#d21c2c` | Lemon illustration fill |
| 3 | Pale Yellow | 939 C | `#feefa1` | "lemons" display type, leaves, FRESH / ZESTY labels |

## 2. Bloom — tan → purple → orange

| # | Color | Pantone | Hex | Used for |
|---|-------|---------|-----|----------|
| 1 | Warm Tan | P 15-2 C | `#e7cfa4` | Poster background |
| 2 | Deep Plum | P 95-16 C | `#371540` | "bloom" wordmark, stems, geometric details |
| 3 | Burnt Orange | P 30-8 C | `#db6427` | Flower shapes |

## 3. Autumn Vibes — maroon → beige → orange

| # | Color | Pantone | Hex | Used for |
|---|-------|---------|-----|----------|
| 1 | Autumn Maroon | 2350 U | `#973d39` | Poster background |
| 2 | Oat Beige | P 24-9 U | `#f2dfc3` | "Autumn Vibes" title, light oak leaves |
| 3 | Harvest Orange | P 14-6 U | `#ec963e` | Orange oak leaves |

## Fonts

Three categories, inventoried in `fonts.json` and ready to use via
`fonts/fonts.css` (`<link rel="stylesheet" href="fonts/fonts.css">`):

| Category | Family | Use for | License |
|----------|--------|---------|---------|
| **Display** | ZT Bros Oskon 90s (Extra Light / Light / Regular + italics) | Headlines, poster titles, big expressive type | User-provided — verify license before publishing |
| **Readable** | Inter (variable, wght 100–900 + italic) | Body text, paragraphs, UI copy — maximum legibility at small sizes | SIL OFL 1.1 |
| **Mono** | Space Mono (Regular / Bold + italics) | Hex codes, swatch labels, captions, code snippets | SIL OFL 1.1 |

Suggested pairing: **ZT Bros Oskon 90s** for headlines, **Inter** for body,
**Space Mono** for hex codes and labels.
