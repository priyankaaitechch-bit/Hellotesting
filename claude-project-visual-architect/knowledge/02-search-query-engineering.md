# 02 — SEARCH QUERY ENGINEERING

How CLIP HUNTER builds YouTube search queries and refines them when web search doesn't land the clip on the first try.

---

## QUERY FORMULA

```
[SUBJECT] + [SPECIFIC SCENE DESCRIPTOR] + [QUALITY TAG] + [OPTIONAL SOURCE HINT]
```

**Examples:**
- Weak: `Breaking Bad death`
- Strong: `Gus Fring Face Off bomb nursing home death 1080p`
- Strong: `Peter Parker memory wipe goodbye MJ No Way Home ending 4K`

---

## RECIPES BY SITUATION

| Situation | Recipe |
|---|---|
| Specific character scene | `[Character] [emotion/action] [Title] [quality]` |
| Scene pack | `[Title] scene pack [quality]` |
| Twixtor / slow-mo edit | `[Title/Character] twixtor [quality] [raw/no music]` |
| Game cutscenes | `[Game] all cutscenes [quality] no commentary` |
| Character compilation | `[Character] all scenes [Title]` |
| Abstract b-roll | `[Concept] b-roll OR stock footage OR motion graphics` |
| Archival / news | `[Event/Person] [Year] footage OR archive OR documentary` |
| Reaction shot | `[Character] reaction [Event] [Title]` |
| Iconic line | `"[Exact quoted line]"` in quotes |

---

## QUALITY MODIFIERS (pick one)

- `1080p` — safe default
- `4K` / `2160p` — modern content
- `HD` — older content
- `60fps` — action-heavy
- `remastered` / `restored` — classic content
- `upscaled` — AI-upscaled re-uploads

## FORMAT MODIFIERS

- `raw` (anime context = no subs; general = unedited)
- `no music` — preserves original audio
- `no commentary` — removes YouTuber VO
- `no subtitles` / `no subs` — clean frame
- `full scene` / `uncut` / `extended`

## AESTHETIC MODIFIERS

- `cinematic` — color-graded uploads
- `edit` — aesthetic fan edit
- `AMV` — anime music video
- `tribute` — often higher-quality fan cuts

---

## FAILURE PATTERNS → FIX

| Failure | Fix |
|---|---|
| Too generic | Add film/show/game identifier |
| Misspelled name | Canonical spelling always — `Daenerys` not `Danerys` |
| Ambiguous title | Add year or franchise qualifier |
| Too recent | Add specific air date or episode number |
| Too low-res results | Add `1080p`/`4K` modifier |
| Subtitles / dubs unwanted | Add `raw`/`no subs` |

---

## ESCALATION LADDER (when YouTube search fails)

1. YouTube with refined query
2. YouTube with channel filter (`@channel [query]`)
3. Reddit r/scenepacks + show-specific subs
4. Google `site:youtube.com "exact phrase"` search
5. Bilibili.com (anime/Asian cinema)
6. archive.org (pre-1970s, public domain)
7. Vimeo (student/indie/press)
8. Dailymotion (European mirror, takedown-resistant)
9. Twitter/X `filter:native_video`
10. Reverse image search the screenshot → trail it back

---

## FAST TIPS

- Two queries always beat one — give user a broad AND narrow version
- Quote iconic lines directly — `"I am the one who knocks"` in quotes often lands the exact scene
- Add year for ambiguous titles — `Joker 2019` vs `Joker 2008` vs `Joker 1989`
- Episode titles narrow massively — `Breaking Bad Ozymandias` beats `Breaking Bad S5E14`
- Channel handles change — if a specific handle fails, try the creator's actual name
