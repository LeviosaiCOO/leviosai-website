# bond — self-hosted font licenses

These are the license texts for the three typefaces used across the bond
marketing site (`/bond`). Each font is bundled here (in `public/fonts/bond/`)
along with its license, which is all the OFL / ITF Free Font License require —
no on-page attribution is needed. Keep this folder next to the `.woff2` files
if the fonts are ever moved.

| Typeface | Role on the site | File | License | License file | Source |
|----------|------------------|------|---------|--------------|--------|
| **Zodiak** | display serif — headlines (`.b-display`) | `zodiak-variable.woff2`, `zodiak-variable-italic.woff2` | ITF Free Font License (FFL) | `zodiak-ITF-FFL.txt` | Fontshare (Indian Type Foundry) — fontshare.com/fonts/zodiak |
| **Sentient** | body serif (`.bond-root`, `.b-body`) | `sentient-variable.woff2` | ITF Free Font License (FFL) | `sentient-ITF-FFL.txt` | Fontshare (Indian Type Foundry) — fontshare.com/fonts/sentient |
| **Martian Mono** | telemetry / mono caps (`.b-tele`, CTAs) | `martian-mono-var-latin.woff2` (Latin subset) | SIL Open Font License 1.1 | `martian-mono-OFL.txt` | Google Fonts — fonts.google.com/specimen/Martian+Mono |

## Terms in brief

- **ITF Free Font License (Zodiak, Sentient):** free for commercial and personal
  use, including web embedding. Do **not** sell the font files themselves or
  redistribute them as a standalone product. The shipped `.woff2` files are
  served unmodified (not subset), as the FFL requests.
- **SIL OFL 1.1 (Martian Mono):** free for commercial use and web embedding.
  If redistributed, the license and copyright notice must travel with the font
  (that's this file + `martian-mono-OFL.txt`). The bundled `.woff2` is a Latin
  subset served under a renamed family; the OFL permits modification and subsetting.

`@font-face` declarations live in `app/bond/bond.css`.
