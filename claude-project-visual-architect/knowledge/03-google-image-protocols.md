# 03 — GOOGLE IMAGE PROTOCOLS

How CLIP HUNTER builds the single `IMG:` line in each breakdown block. Keep it lean — one precise query per line.

---

## QUERY FORMULA

```
[SUBJECT] + [SPECIFIC CONTEXT] + [QUALITY SIGNAL]
```

Bad: `Gus Fring`
Good: `Gus Fring Pollos Hermanos yellow shirt still high resolution`

---

## USER APPLIES THESE FILTERS (mention only if the query specifically needs them)

Google Images → Tools dropdown:
- **Size → Large** — almost always; filters thumbnails
- **Type → Photo** — for real photography/stills
- **Type → Clip Art** — illustrations, logos, icons
- **Color → Black and white** — noir/retro mood
- **Color → Transparent** — logos as PNG
- **Usage Rights → Creative Commons** — safer commercial use

CLIP HUNTER mentions these filters only when they meaningfully narrow results. Default queries assume Size:Large is on.

---

## QUERY RECIPES BY USE CASE

| Use case | Query template |
|---|---|
| Film / TV still | `[Film/Show] [Character] [scene] still high resolution` |
| Press / promo portrait | `[Character] [Show] promo portrait` |
| Historical figure | `[Person] [Year] photograph archival` |
| Quote card background | `[Subject] close up dark cinematic` |
| Comic panel style | `[Character] comic book illustration [mood]` |
| Location / architecture | `[Location] exterior wide photograph` |
| Abstract concept | `[Concept] symbolic imagery cinematic` |
| Data / chart | `[Topic] chart infographic [year]` |

---

## PREFERRED SOURCES BY NICHE

| Niche | Best sources |
|---|---|
| Film / TV | IMDb media, TMDB, Film Grab, EvanERichards, Reddit r/MovieDetails |
| Games | Steam store, MobyGames, press kits, ArtStation |
| Anime | MyAnimeList, AniDB, Zerochan, Pinterest |
| Historical / real people | Wikimedia Commons, Library of Congress, Getty (paid), AP Images (paid) |
| Cartoons | Fandom wikis (per show), DeviantArt, official press kits |
| Free CC photography | Unsplash, Pexels, Pixabay, Wikimedia Commons, Flickr CC filter |

---

## REVERSE IMAGE SEARCH (for hard cases)

When user has a low-res reference or can't find the origin:
1. **Yandex Images** — best hit rate for media stills and screenshots
2. **Google Lens** — for context + higher-res alternatives
3. **TinEye** — for exact duplicates at different resolutions

---

## RESOLUTION STANDARDS

- Full-frame in 1080p video: min 1920x1080
- Full-frame in 4K video: min 3840x2160
- Ken Burns pan: 2x target resolution
- Under target? Suggest Topaz Gigapixel / Upscayl upscale, OR partial-frame (PiP) use

---

## INTEGRATION RULE

Each breakdown block gets **one** IMG query. If the block genuinely needs two distinct images (e.g., split screen showing two things), that's a valid exception — give two, not more.

If motion is the whole beat and no still applies, drop the IMG line entirely from that block.
