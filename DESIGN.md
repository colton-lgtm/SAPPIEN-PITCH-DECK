# SAP(P)IEN Sponsorship Deck — Design System

Source: Figma Slides `LQwB1UFotpgVDhWzUYt3sX` (14 slides, 1920×1080).

## Colour

| Token | Hex | Use |
|---|---|---|
| `ink` | `#1E1D18` | Slide background, hazard-tape base, text on orange/bone |
| `panel` | `#2B2A22` | Cards, segment chips, bands, hairline rules |
| `panel-2` | `#36352C` | Image placeholders |
| `olive` | `#4A4A30` | Photo placeholders, SHOOT phase block |
| `bone` | `#F4F0E4` | Headlines and body text |
| `sand` | `#C8B98F` | Card labels, secondary accent bar, sub-headers |
| `stone` | `#B9B29C` | Breadcrumb labels, stat captions, muted body |
| `orange` | `#E8561C` | Primary accent: (P) in wordmark, accent bars, hazard stripes, hero numbers, price panel |
| `orange-lt` | `#F07A45` | Orange-on-dark labels (card titles, list numerals) |

Orange is used sparingly on most slides; one of three items is highlighted orange, the others stay bone/sand (e.g. "ONE MEAL. / **ONE CHASE.** / EVERY WEEK.").

## Typography

| Role | Font | Sizes | Notes |
|---|---|---|---|
| Display | **Big Shoulders Stencil Display ExtraBold** | 44–230 (titles 84–150, hero 180–230, numerals 44–100) | All caps, tight leading |
| Labels / UI | **JetBrains Mono** Medium & Bold | 16–30 | All caps, letter-spacing 8–20% (breadcrumbs 15%, card titles 12%) |
| Body | **Inter** Regular | 21–32 (Semi Bold 44 for pitch line) | Sentence case |
| Pull quote | Playfair Display Bold | ~32 | Used once (slide 6) |

Wordmark: `SAP(P)IEN` in Big Shoulders 190, with `(P)` in orange and the rest bone.

## Layout grid

- 80px outer margin left/right; 1760px content width
- Breadcrumb at y=70: `SAP(P)IEN  /  SECTION   ·   NN / 14` (JetBrains Mono 20, stone)
- Accent bar under breadcrumb: 80×6 orange, ~40–100px below it
- Title follows the accent bar
- Three-column rhythm: 560px cards, 40px gutters (x = 80 / 680 / 1280)
- Split layouts: text left (~860–960px), photography right with a 320px dark fade into the image
- Cards: `panel` fill, 8px top bar (sand, or orange for the highlighted card), 1px bone@10% stroke (or orange→panel gradient stroke when highlighted), 36px padding, square corners

## Effects (on every slide)

1. **Vignette**: full-bleed radial gradient, transparent centre → `#0A0908` @30% at the edges
2. **Grain**: full-bleed rect with a Figma NOISE effect, white @9%
3. **Orange glow on text**: drop shadow, blur 26, `#E8561C` @38%, on orange numerals/titles (neon/ember feel)
4. **Title shadow**: drop shadow, blur 12, black @40%, on bone headlines
5. **Ambient glow**: blurred orange radial ellipse (layer blur 60, orange @25–35%) behind hero type on slides 1, 9, 13, 14
6. **Photo tint**: every photo carries an extra orange @7% fill overlay to warm it
7. **Image fade**: linear `ink` @95% → 0 gradient, 85–320px wide, blending photos into the dark side

## Signature motifs

- **Hazard tape**: 100px band at bottom (y=980) of cover and closing slides. 26px orange stripes every 52px rotated −30°, on `ink`, with a centred `ink` tag reading "APEX MEETS APEX" (JetBrains Mono Bold 30, 20% tracking)
- Apex Pursuit lion crest logo, top-left on the cover
- Big stat blocks: 270px-wide orange or sand top rule + giant stencil number + mono caption
- Full-colour panels for emphasis: orange left panel on the price slide (text in `ink`), and orange/sand/olive blocks in the timeline

## Slide map

1. Cover: wordmark, subtitle, hazard tape
2. The Concept: split text/photo, enrichment card
3. The Experience: "SURVIVAL OF THE FITTEST", glowing value words
4. How It Works: three photo+step cards
5. Safety / Welfare: three cards
6. The Talent: Bob bio, stat column, pull quote
7. The Beast & The Beasts
8. Audience / Reach: segment chips, metrics, channels band
9. Why [Brand]: lockup, three bottom blocks
10. Brand Integration: 2×2 image cards
11. The Package: orange price panel + list of deliverables
12. Activations: three tall cards
13. Timeline: "22 WEEKS" with proportional phase bars
14. Next Steps: "LET'S TALK.", three steps, QR, hazard tape

## V2 additions (17 slides)

- **Fixed header** on every content slide: breadcrumb at (80, 64), `NN / 17` right-aligned to x=1840, 80×6 orange accent at y=104.
- **One glow per slide.** The accent word of the title is orange with the glow. Everything else is bone with the 12px black shadow.
- **Status chips** (JetBrains Mono Bold 16, 12% tracking, 10px dot):
  - `done`: solid orange, ink text
  - `dark`: ink fill, bone text, orange dot
  - `prog`: orange outline
  - `exp`: sand outline
  - `tbd`: dashed stone outline
- **[BOB: INSERT] placeholders:** dashed orange 1.5px outline, orange @8% fill, JetBrains Mono Medium 17, orange-lt text. An ink variant is used on orange slides.
- **Image placeholders:** `panel-2` fill, dashed orange 2px stroke `[14,10]`, centred `[ DROP: … ]` label.
- **Ledgers (Financials):** Inter 20 labels, JetBrains Mono Bold 22 values right-aligned to the column edge, bone @10% hairlines, totals in Big Shoulders orange.
- **Tonal arc:** dark slides throughout, with orange panels on Revenue (10) and a full-orange slide for The Ask (16). Hazard tape bookends slides 1 and 17.
- **Speaker notes:** every slide carries the outline text that was condensed on the slide, plus TODOs.
