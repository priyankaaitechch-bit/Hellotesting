# GOOGLE IMAGE SEARCH PROTOCOLS

Stills and static images are a first-class asset class for video essays. They're used for quote cards, chapter inserts, comic-panel frames, cutaway stills, reference inserts, and moments when a video clip is unavailable.

This file contains the query patterns and filter discipline required to land the exact image on the first page of results.

---

## WHY STILLS MATTER IN VIDEO ESSAYS

Stills serve four distinct roles:

1. **Punctuation frames** — hold on a single still for 2–4 seconds to let a line breathe
2. **Typography beds** — the background behind an on-screen quote
3. **Comic-panel inserts** — with borders + halftone overlay for stylized moments
4. **Fallback for unavailable video** — when a scene clip can't be sourced, a sharp high-res still can carry the moment

---

## THE IMAGE QUERY FORMULA

```
[SUBJECT] + [SPECIFIC CONTEXT / SCENE] + [QUALITY SIGNAL] + [SOURCE HINT IF NEEDED]
```

**Examples:**
- Bad: `Gus Fring`
- Editor-grade: `Gus Fring half face burned Face Off final scene still high resolution`

---

## GOOGLE IMAGE FILTERS YOU MUST USE

After running the search, ALWAYS apply the filter chain:

| Filter | When to use |
|---|---|
| **Tools → Size → Large** | Always — filters out small/thumbnail-only results |
| **Tools → Type → Photo** | For real photography / film stills |
| **Tools → Type → Clip Art** | For illustrations / icons / diagrams |
| **Tools → Color → Black and white** | For noir / retro / investigative mood |
| **Tools → Color → Transparent** | For logos / PNG assets |
| **Tools → Usage Rights → Creative Commons licenses** | For safer commercial use |
| **Tools → Time → Past year** | For recent events / post-training content |

---

## QUERY RECIPES BY USE CASE

### Recipe 1 — Film / TV Still
`[Film or Show Name] + [Character] + [specific scene] + still`

Examples:
- `Breaking Bad Gus Fring half burned face still high resolution`
- `The Godfather Michael Corleone baptism still`
- `No Country for Old Men Anton Chigurh coin toss still`

### Recipe 2 — Character Press / Promo Image
`[Character Name] + [Show/Film] + promo portrait`

Examples:
- `Tony Soprano HBO promo portrait high resolution`
- `Heisenberg Walter White hat press still`

### Recipe 3 — Historical Figure / Event
`[Person or Event] + [Year] + photograph archival`

Examples:
- `Einstein tongue photograph 1951 archival`
- `Apollo 11 moon landing Buzz Aldrin archival NASA`

### Recipe 4 — Quote Card Background
`[Subject] + close up dark cinematic background`

Examples:
- `Gus Fring close up face dark cinematic still`
- `Don Draper silhouette office window`

### Recipe 5 — Comic-Panel Style Frame
`[Character] + comic book illustration + [mood]`

Examples:
- `Batman comic book illustration noir Frank Miller`
- `Spider-Man comic book panel silver age`

### Recipe 6 — Architectural / Location Reference
`[Location or Building] + exterior wide shot photography`

Examples:
- `Pollos Hermanos restaurant Albuquerque exterior photograph`
- `World Trade Center exterior 1995 photograph`

### Recipe 7 — Abstract Concept Imagery
`[Concept] + symbolic imagery + [aesthetic]`

Examples:
- `loneliness symbolic imagery cinematic dark`
- `greed money pile symbolic photography`

### Recipe 8 — Data / Chart / Infographic
`[Topic] + chart infographic + [year]`

Examples:
- `2008 financial crisis S&P 500 chart infographic`
- `smartphone adoption worldwide chart by year`

---

## PREFERRED IMAGE SOURCES BY TYPE

### Film & TV stills
- **IMDb** (scroll to Media → Photos tab for official stills)
- **TMDB (themoviedb.org)** — excellent curated stills
- **Film Grab (film-grab.com)** — curated cinematographer-quality frames
- **EvanERichards.com** — DP-level frame breakdowns for major films
- **Reddit r/MovieDetails** — screenshots with context
- **FanArt.tv** — promotional stills + fan art

### Video game stills
- **Official press kits** — search `[Game Name] press kit`
- **Steam store pages** (scroll to screenshots)
- **MobyGames.com** — comprehensive screenshot archives
- **DeviantArt** — fan art + game stills

### Anime stills
- **MyAnimeList (myanimelist.net)** — official promo images
- **AniDB.net** — character databases
- **Zerochan.net** — high-res anime art
- **Pinterest** — massive aggregator (caveat: verify resolution)

### Historical / archival photography
- **Wikimedia Commons (commons.wikimedia.org)** — free, often high-res
- **Library of Congress Digital Collections**
- **U.S. National Archives**
- **Getty Images** (paid, licensed)
- **Associated Press Images** (paid)
- **Bettmann Archive** (through Getty)
- **archive.org** — massive mixed archive

### Real people / journalism
- **Getty Images** (paid)
- **Reuters Pictures** (paid)
- **AP Images** (paid)
- **Wikipedia** (for public domain portraits)

### Free / CC-licensed photography
- **Unsplash.com**
- **Pexels.com**
- **Pixabay.com**
- **Wikimedia Commons**
- **Flickr Creative Commons** (filter by CC license)

---

## ADVANCED — REVERSE IMAGE SEARCH

When you need a specific frame but don't know where it's from, or when you need higher-res versions of a known image:

1. **Google Lens / Google Images → "Search by image"** — paste a URL or upload the image
2. **TinEye.com** — often finds higher-res versions of the same image
3. **Yandex Images (yandex.com/images)** — often beats Google for niche content, especially for recognizing character screenshots
4. **Bing Visual Search** — third option worth trying

### Typical reverse search flow
1. You have a low-res reference
2. Run it through Yandex first (highest hit rate for media stills)
3. Then Google Lens for context
4. Then TinEye for exact duplicates at different resolutions

---

## RESOLUTION STANDARDS FOR VIDEO ESSAYS

- **Minimum acceptable width for background use:** 1920px
- **Minimum for full-screen display in 1080p video:** 1920 x 1080px
- **Minimum for full-screen display in 4K video:** 3840 x 2160px
- **For Ken Burns pan-and-zoom:** 2x target resolution (so 4K pan → 7680px source)

If a source image is below target resolution, **note this in the breakdown** and suggest either:
- AI upscaling (Topaz Gigapixel / Upscayl)
- Use the image at partial-frame size (picture-in-picture)
- Find an alternative

---

## LICENSING QUICK REFERENCE

| Source | License | Safe for monetized YouTube? |
|---|---|---|
| Wikimedia Commons | Mostly CC-BY-SA or Public Domain | Yes (check individual image) |
| Unsplash / Pexels / Pixabay | Custom permissive | Yes |
| Film stills from IMDb | Promotional / fair use | Risky — better to use under commentary/criticism fair use |
| Getty / AP / Reuters | Proprietary | No without license |
| Reddit screenshots | Uploader's rights | Risky |
| AI-generated (via Midjourney, DALL-E, SDXL) | Varies by platform ToS | Usually yes |

For video essays using film/TV/game stills under fair use for criticism and commentary, most creators proceed — but this is the user's legal call, not yours.

---

## INTEGRATION WITH BREAKDOWN OUTPUT

Every breakdown block's 🖼️ SECONDARY ASSET section should contain:

1. **3+ Google Image search queries** (editor-grade, using formulas above)
2. **Explicit filter suggestions** (e.g., "Tools → Size: Large, Type: Photo")
3. **Preferred source** (e.g., "Film Grab for Breaking Bad frames")
4. **Fallback source** if primary search is empty

Example of good secondary-asset output:

```
🖼️ SECONDARY ASSET — GOOGLE IMAGES / STILLS

Google Images search terms:
1. `Gus Fring half face burned still Face Off` — apply filter: Size: Large, Type: Photo
2. `Gus Fring tie adjustment final scene still` — apply filter: Size: Large
3. `Giancarlo Esposito Breaking Bad Face Off press still` — apply filter: Type: Photo

Preferred image sources: Film Grab (film-grab.com) has curated Breaking Bad frames. Fallback: Reddit r/breakingbad top posts filtered by "final scene".

Resolution check: Need minimum 1920px wide for full-frame use. If primary result is below this, upscale with Topaz Gigapixel.
```
