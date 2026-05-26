# Sports Comparison Image Prompt Architect — Claude Project

A specialized Claude Project that takes a one-line input (e.g., `Football`, `4 players NBA`, `F1 - Senna, Schumacher`) and returns a hyper-detailed image-generation prompt + a short Facebook caption — ready to paste into Grok, Gemini, or ChatGPT image to produce viral split-screen sports comparison posts.

---

## What this project does

You type → Claude outputs:

1. A **detailed image prompt** (copy-paste into any AI image tool, ideally Grok)
2. A **5-10 word Facebook caption** with emoji

That's it. No chit-chat. No analysis. Just the two deliverables.

---

## How to set up the Claude Project

1. Go to [claude.ai/projects](https://claude.ai/projects) and create a new project.
2. **Name:** `Sports Comparison Image Prompt Architect`
3. **Custom Instructions:** Paste the entire contents of [`PROJECT_INSTRUCTIONS.md`](./PROJECT_INSTRUCTIONS.md).
4. **Knowledge files:** Upload these files as project knowledge:
   - [`knowledge/01-superstar-rosters.md`](./knowledge/01-superstar-rosters.md)
   - [`knowledge/02-layout-templates.md`](./knowledge/02-layout-templates.md)
   - [`knowledge/03-photorealism-directives.md`](./knowledge/03-photorealism-directives.md)
   - [`knowledge/04-heading-pool.md`](./knowledge/04-heading-pool.md)
   - [`knowledge/05-identifier-guide.md`](./knowledge/05-identifier-guide.md)
   - [`EXAMPLES.md`](./EXAMPLES.md)
5. Save and start chatting.

---

## How to use

Just type a one-line input. Claude will reply with a prompt + caption.

### Supported input formats

| Format | Example |
|---|---|
| Sport name only (defaults to 2 players) | `Football` |
| Sport + count | `3 players NBA` or `NBA 3` |
| Sport + named players | `Football - Ronaldo, Messi` |
| Sport + 3 named players | `NBA - Jordan, LeBron, Kobe` |
| Sport + 4 named players (Mount Rushmore) | `F1 - Senna, Schumacher, Hamilton, Verstappen` |
| Sport with rivalry phrasing | `Boxing Ali vs Tyson` |

### Supported sports

Football (Soccer), NFL, NBA, Cricket, Formula 1 (F1), Tennis, Golf, Boxing, MMA / UFC.

(For other sports not listed, Claude will fall back to country flags as identifiers.)

---

## End-to-end workflow (how to use the output)

1. **Type input** → e.g., `Football`
2. **Claude returns prompt + caption**
3. **Open Grok** (recommended — handles celebrity faces best) and select **2:3 Tall** aspect ratio
4. **Paste the prompt** → generate image
5. **Crop the image** to 4:5 (1080×1350) using [birme.net](https://www.birme.net) or Canva
6. **Post on Facebook** with the caption Claude provided

The top 10% / bottom 10% of the generated image are intentionally empty, so the 4:5 center crop never cuts off any important elements.

---

## File structure

```
claude-sports-comparison-architect/
├── PROJECT_INSTRUCTIONS.md          # Main system prompt (paste into Claude Project)
├── README.md                        # This file
├── EXAMPLES.md                      # Sample input → output pairs
└── knowledge/
    ├── 01-superstar-rosters.md      # Player tier lists per sport
    ├── 02-layout-templates.md       # 2 / 3 / 4 player layout specs
    ├── 03-photorealism-directives.md # Anti-AI photography directives
    ├── 04-heading-pool.md           # Heading text variations per sport
    └── 05-identifier-guide.md       # Country flag vs team logo decision guide
```

---

## Tips for best results

- **Use Grok** for the actual image generation — it handles real celebrity faces better than Gemini or ChatGPT.
- **Always select 2:3 Tall** aspect ratio in Grok before pasting the prompt.
- **Center-crop to 4:5** before posting — the prompt's safe-zone rule guarantees nothing important is lost.
- **Vary the heading** by re-running the same input — Claude rotates headings from the pool, keeping your feed fresh.
- **Add manual logos in Canva** if AI-rendered team logos look distorted (common issue for sports with team-based identifiers like NBA, NFL).

---

## Future expansion ideas

- Add more sports (rugby, hockey, baseball, esports)
- Add more layout variants (head-to-head close-up, vs trophy in middle)
- Add caption variation packs (Hindi, English, Hinglish)
- Add per-sport hashtag pack
