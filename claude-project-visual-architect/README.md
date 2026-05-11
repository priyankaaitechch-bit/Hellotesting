# VISUAL ARCHITECT — Claude Project Setup Guide

A pro-level Claude Project that transforms video essay scripts into paragraph-by-paragraph visual sourcing plans with editor-grade YouTube search terms, Google Image queries, canonical scene references, and fallback strategies.

Built to replace generic Gemini Gem setups that produce inaccurate or shallow results.

---

## WHAT THIS PROJECT DOES

Feed it a video essay script. It will:

1. **Deep-analyze the script** — thesis, emotional arc, vibe, aesthetic prescription, confidence audit
2. **Wait for your signal** — only breaks down sections you explicitly send
3. **Paragraph-level visual breakdown** — for every paragraph:
   - Emotional function of the paragraph
   - Full visual direction (camera, pacing, typography, audio cues)
   - Primary real-footage source (with canonical references where possible)
   - 4+ YouTube search terms, editor-grade
   - Google Image search terms
   - Stock/motion-graphics fallbacks
   - AI generation fallback (only when justified)
   - Sourcing confidence rating

---

## SETUP STEPS

### Step 1 — Create a new Claude Project
Go to claude.ai → Projects → Create Project. Name it "Visual Architect" or similar.

### Step 2 — Paste Project Instructions
Copy the entire contents of `PROJECT_INSTRUCTIONS.md` into the Project's "Custom instructions" / "Project instructions" field.

### Step 3 — Upload Knowledge Files
Upload these five files to the Project's Knowledge panel:

1. `knowledge/01-youtube-sourcing-database.md`
2. `knowledge/02-search-query-engineering.md`
3. `knowledge/03-google-image-protocols.md`
4. `knowledge/04-visual-grammar-reference.md`
5. `knowledge/05-genre-playbooks.md`

### Step 4 — Prepare Your Script

Follow the format in `SCRIPT_INPUT_TEMPLATE.md`. The 5 things that maximize output quality:

- Title
- Target video length (minutes)
- Target channel / style reference (1-2 YouTube channels whose editing you want to emulate)
- Aesthetic direction (cinematic / comic book / retro / clean explainer / etc.)
- The full script with section headers

### Step 5 — Paste script → receive deep analysis → send sections one by one

---

## WORKFLOW

```
[You paste title + full script]
       ↓
[Claude: Script Received + Deep Analysis]
       ↓
[You: "Proceed with SECTION 1" or paste a paragraph]
       ↓
[Claude: Paragraph-by-paragraph breakdown with all asset sources]
       ↓
[Repeat per section / paragraph]
```

---

## WHY THIS BEATS A GENERIC GEM

| Gemini Gem (basic) | Visual Architect (this project) |
|---|---|
| Line-by-line (loses paragraph context) | Paragraph-level by default, preserves story beat |
| Generic search terms | 4+ ranked, editor-grade queries per line |
| No Google Image search | Separate image-sourcing pipeline |
| Defaults to green screen | Green screen requires justification |
| No confidence signal | Explicit 🟢🟡🔴 confidence rating per asset |
| No canonical scene DB | References episode + approximate timestamp for famous content |
| No vibe lock | Locks aesthetic prescription before breakdown |
| Fabricates sources | Honest about training cutoff and search-only mode |

---

## HONEST LIMITATIONS

- Claude cannot browse YouTube live (unless your Claude plan has web search enabled in Projects).
- For canonical popular content (top ~1000 films, top shows, AAA games), episode + approximate timestamp references are reliable.
- For obscure / recent / niche content, you get search-term strategy only — no fabricated URLs.
- Always treat timestamps as approximate — verify before cutting.

---

## FILES IN THIS PROJECT

```
claude-project-visual-architect/
├── README.md                                 (this file)
├── PROJECT_INSTRUCTIONS.md                   (paste into Claude Project custom instructions)
├── SCRIPT_INPUT_TEMPLATE.md                  (how to format scripts you send)
├── EXAMPLE_OUTPUT.md                         (example of what output looks like)
└── knowledge/
    ├── 01-youtube-sourcing-database.md       (channels + ecosystems by content type)
    ├── 02-search-query-engineering.md        (how to construct precise queries)
    ├── 03-google-image-protocols.md          (image search patterns)
    ├── 04-visual-grammar-reference.md        (cinematography + editing vocabulary)
    └── 05-genre-playbooks.md                 (per-genre sourcing protocols)
```
