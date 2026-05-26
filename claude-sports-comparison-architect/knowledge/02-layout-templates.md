# Layout Templates — 2 / 3 / 4 Player Compositions

All layouts use **2:3 vertical aspect ratio** (e.g., 1080×1620 px). The image will be center-cropped to **4:5 (1080×1350)** before posting to Facebook. Therefore the **top 10% and bottom 10% are dead zones** — only background, no key elements.

The visible safe area after cropping is the **central 80%** of the original image.

---

## TEMPLATE A — 2 PLAYERS (Vertical Split)

Use this when the user requests 2 players (default) or names 2 players.

### Vertical zones (top to bottom)

| Zone | Vertical % | Contents |
|---|---|---|
| Dead zone | 0–10% | Pure black/dark gradient background, NO elements |
| Heading banner | 10–22% | Solid black banner, full-width, centered bold heading text in gold + white |
| Identifier row | 22–32% | Two circular flag/logo badges — top-left + top-right |
| Main subjects | 32–78% | Vertical split into LEFT half + RIGHT half, with center gold divider |
| Nameplate row | 78–90% | Two cream/ivory plaques side-by-side — one under each subject |
| Dead zone | 90–100% | Pure black/dark gradient background, NO elements |

### Embed in prompt

```
LAYOUT: 2-PLAYER VERTICAL SPLIT, 2:3 aspect ratio.

TOP 10%: pure black dead zone, NO elements.

10%-22% HEADING BANNER: full-width solid black horizontal band. 
Centered bold text "[HEADING TEXT]". First half of heading in 
metallic gold gradient, second half in clean bright white. Heavy 
condensed sans-serif font (Bebas Neue / Impact). Decorative thin 
gold horizontal lines on left and right of text. Subtle inner glow.

22%-32% IDENTIFIER ROW:
- Top-left: circular [PLAYER 1 IDENTIFIER] badge, ~110px diameter, 
  white border, soft drop shadow.
- Top-right: circular [PLAYER 2 IDENTIFIER] badge, ~110px diameter, 
  white border, soft drop shadow.

32%-78% MAIN SUBJECTS — split vertically into two equal halves with 
a thin elegant gold vertical divider line (with subtle glow) running 
exactly down the center.

LEFT HALF: [PLAYER 1 DESCRIPTION BLOCK]
RIGHT HALF: [PLAYER 2 DESCRIPTION BLOCK]

78%-90% NAMEPLATE ROW: two equal cream/ivory rectangular plaques 
with gold ornamental border, slight rounded corners, soft drop 
shadow — luxury award-certificate style.
- LEFT NAMEPLATE: top line "[PLAYER 1 FIRST NAME]" smaller dark gold 
  serif; bottom line "[PLAYER 1 LAST NAME]" larger bold black serif 
  (Trajan / Playfair Display); small metallic gold heart icon on right.
- RIGHT NAMEPLATE: top line "[PLAYER 2 FIRST NAME]" smaller dark gold 
  serif; bottom line "[PLAYER 2 LAST NAME]" larger bold black serif; 
  small metallic gold heart icon on right.

BOTTOM 10%: pure black dead zone, NO elements.
```

---

## TEMPLATE B — 3 PLAYERS (Vertical Thirds)

Use this when the user requests 3 players or names 3 players.

### Vertical zones

| Zone | Vertical % | Contents |
|---|---|---|
| Dead zone | 0–10% | Pure black, NO elements |
| Heading banner | 10–22% | Solid black banner, full-width, centered bold heading |
| Identifier row | 22–32% | Three circular badges, evenly spaced across the top |
| Main subjects | 32–78% | Vertical split into 3 equal thirds, with two gold dividers |
| Nameplate row | 78–90% | Three cream/ivory plaques side-by-side |
| Dead zone | 90–100% | Pure black, NO elements |

### Embed in prompt

```
LAYOUT: 3-PLAYER VERTICAL THIRDS, 2:3 aspect ratio.

TOP 10%: pure black dead zone, NO elements.

10%-22% HEADING BANNER: full-width solid black horizontal band with 
centered bold text "[HEADING TEXT]" — first half in metallic gold 
gradient, rest in clean bright white. Heavy condensed sans-serif font. 
Decorative gold horizontal lines on both sides. Subtle inner glow.

22%-32% IDENTIFIER ROW:
- Far left: circular [PLAYER 1 IDENTIFIER] badge, ~95px diameter.
- Center: circular [PLAYER 2 IDENTIFIER] badge, ~95px diameter.
- Far right: circular [PLAYER 3 IDENTIFIER] badge, ~95px diameter.
All badges have white borders and soft drop shadows.

32%-78% MAIN SUBJECTS — split vertically into three equal thirds with 
thin elegant gold vertical divider lines (with subtle glow) at 33% 
and 66% widths.

LEFT THIRD: [PLAYER 1 DESCRIPTION BLOCK]
CENTER THIRD: [PLAYER 2 DESCRIPTION BLOCK]
RIGHT THIRD: [PLAYER 3 DESCRIPTION BLOCK]

78%-90% NAMEPLATE ROW: three equal cream/ivory rectangular plaques 
with gold ornamental borders, rounded corners, soft drop shadows.
- LEFT NAMEPLATE: "[PLAYER 1 FIRST NAME]" / "[PLAYER 1 LAST NAME]" + 
  small gold heart icon on right.
- CENTER NAMEPLATE: "[PLAYER 2 FIRST NAME]" / "[PLAYER 2 LAST NAME]" + 
  small gold heart icon on right.
- RIGHT NAMEPLATE: "[PLAYER 3 FIRST NAME]" / "[PLAYER 3 LAST NAME]" + 
  small gold heart icon on right.

BOTTOM 10%: pure black dead zone, NO elements.
```

**Note for 3-player composition:** Frame each subject slightly tighter (chest-up shot rather than full body) so they fit comfortably in narrower thirds.

---

## TEMPLATE C — 4 PLAYERS (2×2 Grid)

Use this when the user requests 4 players or names 4 players. This is the "Mount Rushmore" format.

### Vertical zones

| Zone | Vertical % | Contents |
|---|---|---|
| Dead zone | 0–10% | Pure black, NO elements |
| Heading banner | 10–20% | Solid black banner, full-width, centered bold heading (slightly thinner than 2/3-player) |
| Top row | 20–55% | TOP-LEFT quadrant + TOP-RIGHT quadrant with vertical divider |
| Horizontal divider | 55% (line) | Thin horizontal gold divider with glow, full-width |
| Bottom row | 55–88% | BOTTOM-LEFT quadrant + BOTTOM-RIGHT quadrant with vertical divider |
| Footer (optional) | 88–90% | Subtle gold flourish line OR empty |
| Dead zone | 90–100% | Pure black, NO elements |

Each quadrant contains: small identifier badge in outer corner + chest-up subject + small embedded name label across the bottom strip of the quadrant.

### Embed in prompt

```
LAYOUT: 4-PLAYER 2x2 GRID, 2:3 aspect ratio.

TOP 10%: pure black dead zone, NO elements.

10%-20% HEADING BANNER: full-width solid black horizontal band, 
slightly thinner than standard. Centered bold text "[HEADING TEXT]" — 
first half in metallic gold gradient, rest in clean bright white. 
Heavy condensed sans-serif font. Decorative gold horizontal lines 
on both sides. Subtle inner glow.

20%-55% TOP ROW (split into two equal quadrants by a thin gold 
vertical divider with glow at 50% width):

TOP-LEFT QUADRANT:
- Small circular [PLAYER 1 IDENTIFIER] badge, ~75px diameter, in 
  the upper-outer corner (top-left), white border, drop shadow.
- [PLAYER 1 DESCRIPTION BLOCK — chest-up shot]
- Across the bottom of the quadrant: small cream nameplate strip 
  with gold border, text "[PLAYER 1 FULL NAME]" in bold serif, 
  small gold heart icon.

TOP-RIGHT QUADRANT:
- Small circular [PLAYER 2 IDENTIFIER] badge, ~75px diameter, in 
  the upper-outer corner (top-right), white border, drop shadow.
- [PLAYER 2 DESCRIPTION BLOCK — chest-up shot]
- Bottom strip nameplate with "[PLAYER 2 FULL NAME]" + small gold 
  heart icon.

55% HORIZONTAL DIVIDER: thin elegant gold horizontal line with 
subtle glow, full width, separating top and bottom rows.

55%-88% BOTTOM ROW (split into two equal quadrants by a thin gold 
vertical divider with glow at 50% width):

BOTTOM-LEFT QUADRANT:
- Small circular [PLAYER 3 IDENTIFIER] badge, ~75px diameter, in 
  the lower-outer corner area (left side), white border, drop shadow.
- [PLAYER 3 DESCRIPTION BLOCK — chest-up shot]
- Bottom strip nameplate with "[PLAYER 3 FULL NAME]" + small gold 
  heart icon.

BOTTOM-RIGHT QUADRANT:
- Small circular [PLAYER 4 IDENTIFIER] badge, ~75px diameter, in 
  the lower-outer corner area (right side), white border, drop shadow.
- [PLAYER 4 DESCRIPTION BLOCK — chest-up shot]
- Bottom strip nameplate with "[PLAYER 4 FULL NAME]" + small gold 
  heart icon.

BOTTOM 10%: pure black dead zone, NO elements.
```

**Note for 4-player composition:** Use chest-up or head-and-shoulders portraits only (not full body) since each quadrant is smaller. Each quadrant should feel like a polished individual portrait card that contributes to the whole.

---

## PER-SUBJECT DESCRIPTION BLOCK FORMAT

Each `[PLAYER N DESCRIPTION BLOCK]` placeholder must expand into a paragraph covering:

1. **Identity:** "Hyper-photorealistic [shot type] of [Full Name], age [current/prime age], [hair description], [facial hair description], [build description]"
2. **Iconic outfit:** specific authentic uniform/kit with correct colors and number (e.g., "Argentina national team light blue and white striped jersey with number 10")
3. **Setting:** era-appropriate authentic location (stadium, arena, track, ring, court, course)
4. **Lighting:** match the mood (e.g., "warm golden hour", "cool stadium floodlights", "dramatic spotlight")
5. **Expression:** signature expression and pose ("intense focused stare", "relaxed champion smile", "tongue out — Jordan signature")
6. **Skin texture:** "natural skin texture with visible pores, real sweat, fine details, subsurface scattering"

**Example expansion (Ronaldo):**
> Hyper-photorealistic three-quarter shot of Cristiano Ronaldo, age 40, short modern fade haircut, clean-shaven, athletic muscular build with visible forearm veins. Wearing the official Portugal national team red home jersey with number 7. Inside Estádio do Dragão stadium at night, blue-tinted floodlights illuminating him, slightly blurred crowd in background. Confident intense expression, eyes locked on camera, slight sweat on forehead. Skin shows natural texture with visible pores, real stubble shadow, fine details.

---

## QUICK REFERENCE — WHICH TEMPLATE TO USE

| User input | Template |
|---|---|
| `Football` | Template A (default 2 players, auto-pick Ronaldo vs Messi) |
| `3 players Football` | Template B (auto-pick 3 from football Big-3) |
| `4 players NBA` | Template C (auto-pick NBA Mount Rushmore) |
| `Football - Ronaldo, Messi` | Template A |
| `NBA - Jordan, LeBron, Kobe` | Template B |
| `F1 - Senna, Schumacher, Hamilton, Verstappen` | Template C |
