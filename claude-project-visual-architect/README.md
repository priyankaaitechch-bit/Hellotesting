# CLIP HUNTER — Universal Video Essay Sourcing Project

A cross-platform AI project that turns any video essay script into lean, URL-first, paragraph-by-paragraph visual sourcing output — with exact YouTube timestamps wherever the platform's web search can verify them.

Works on **Claude Projects, ChatGPT Custom GPTs, Gemini Gems, and Grok Projects**. Same instructions, same knowledge files, same output format.

Covers every niche: Hollywood, classic cinema, TV, anime, cartoons, games, documentaries, history, true crime, finance, sci-fi, sports, internet culture.

---

## WHAT IT DOES

For every line of your script, it returns:

1. **Clip description** — what footage to crop (1 sentence)
2. **YouTube URL + timestamp** (when web search is available) OR canonical scene reference + search query
3. **Google Image search query** — for stills and quote cards
4. **Stock fallback** — only when real footage is impossible
5. **Low-confidence warning** — only when sourcing is genuinely uncertain

That's it. No "emotional function" padding. No "color grade" per line. Lean, actionable, editor-ready.

---

## WHY THIS BEATS A BASIC GEM / GPT

| Basic Gem / GPT setup | CLIP HUNTER |
|---|---|
| Guesses URLs from memory | Uses web search for every line (when available) |
| Verbose — 40+ lines per script line | Lean — 6–8 lines per script line |
| Defaults to green screen | Green screen requires justification |
| One-size-fits-all search | Niche-specific playbook (anime ≠ history ≠ game) |
| No confidence signal | Flags only when sourcing is genuinely low-confidence |
| Locks to one platform | Same prompt works on Claude, ChatGPT, Gemini, Grok |

---

## SETUP — 3 MINUTES

### For ChatGPT Custom GPT
1. Go to ChatGPT → Explore GPTs → Create
2. Paste `PROJECT_INSTRUCTIONS.md` into the "Instructions" field
3. Upload the 5 knowledge files (see below) under "Knowledge"
4. **Enable "Web Browsing"** capability — critical for URL verification
5. Save

### For Claude Projects
1. Go to claude.ai → Projects → Create Project
2. Paste `PROJECT_INSTRUCTIONS.md` into the "Custom instructions" field
3. Upload the 5 knowledge files under "Project knowledge"
4. **Enable "Web search"** in project settings (paid plans)
5. Save

### For Gemini Gems
1. Go to gemini.google.com → Gems → Create new Gem
2. Paste `PROJECT_INSTRUCTIONS.md` into the "Instructions" field
3. Upload the 5 knowledge files under "Knowledge"
4. Web grounding is on by default
5. Save

### For Grok Projects (X Premium)
1. Create a new Project in Grok
2. Paste `PROJECT_INSTRUCTIONS.md` into project instructions
3. Add knowledge files as attachments
4. Grok's real-time search is on by default — this is where Grok shines
5. Save

---

## KNOWLEDGE FILES TO UPLOAD

```
knowledge/01-youtube-sourcing-database.md    (channels by niche — films, games, anime, docs, etc.)
knowledge/02-search-query-engineering.md     (how to build queries that land the clip)
knowledge/03-google-image-protocols.md       (image search recipes + filter discipline)
knowledge/04-visual-grammar-reference.md     (cinematography vocab — for context only)
knowledge/05-genre-playbooks.md              (per-niche sourcing protocols)
```

---

## USAGE FLOW

```
1. You paste TITLE + NICHE + VIBE + REFERENCE CHANNELS + full script
       ↓
2. AI locks context (one short block, no breakdown)
       ↓
3. You send a paragraph OR say "Proceed with SECTION X"
       ↓
4. AI returns line-by-line breakdown with YouTube URLs + image queries
       ↓
5. Your editor clicks the URLs, jumps to the timestamps, starts cutting.
```

See `SCRIPT_INPUT_TEMPLATE.md` for the exact input format.
See `EXAMPLE_OUTPUT.md` for what output looks like at target quality.

---

## THE URL QUESTION — HONEST ANSWER

- **Grok (X Premium):** Has live real-time search baked in. Returns real URLs + timestamps reliably. Best platform for this project.
- **ChatGPT (with Browsing enabled):** Returns real URLs via browser tool. Reliable.
- **Gemini (grounding on):** Returns real URLs via search grounding. Reliable.
- **Claude (web search enabled):** Returns real URLs. Reliable on paid plans.
- **Without any web search:** Falls back to canonical scene references (Show S4E13 ~38:00) + precise search queries. Still useful, just not clickable.

The instructions explicitly tell the AI: **never fabricate URLs.** If web search is off or uncertain, it returns search queries instead of made-up links.

---

## FILES IN THIS PROJECT

```
claude-project-visual-architect/
├── README.md                             (this file)
├── PROJECT_INSTRUCTIONS.md               (paste into system instructions — works on all 4 platforms)
├── SCRIPT_INPUT_TEMPLATE.md              (how to format scripts you send)
├── EXAMPLE_OUTPUT.md                     (benchmark for what pro-grade output looks like)
└── knowledge/
    ├── 01-youtube-sourcing-database.md
    ├── 02-search-query-engineering.md
    ├── 03-google-image-protocols.md
    ├── 04-visual-grammar-reference.md
    └── 05-genre-playbooks.md
```

---

## FOLDER NAME NOTE

The folder is named `claude-project-visual-architect/` for historical reasons, but the content is fully platform-agnostic. Rename it if you prefer — nothing inside depends on the folder name.
