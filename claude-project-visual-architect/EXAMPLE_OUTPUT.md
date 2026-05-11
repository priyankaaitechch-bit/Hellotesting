# EXAMPLE OUTPUT

What the CLIP HUNTER project produces when working correctly. Use this as a quality benchmark — lean, URL-first, no fluff.

---

## INPUT

```
TITLE: Why Gus Fring Lost Control
NICHE: TV breakdown (Breaking Bad character study)
VIBE: Dark cinematic, patient
REFERENCE CHANNELS: Wendigoon + The Cinema Cartography

[paste full script with section headers]
```

---

## PHASE 1 RESPONSE

```
📌 LOCKED

Title: Why Gus Fring Lost Control
Niche: TV breakdown (Breaking Bad character study)
Vibe: Dark cinematic, patient
Key entities: Gus Fring, Hector Salamanca, Walter White, Max, Don Eladio, Tyrus, Jesse
Sections: 8 (HOOK + SECTION 1–7)
Style match: Wendigoon + The Cinema Cartography

Ready. Send a paragraph, or say "Proceed with SECTION X".
```

---

## PHASE 2 RESPONSE (user said "Proceed with HOOK")

```
━━━ 1 ━━━
"For four seasons of Breaking Bad, Gus Fring did not make a single mistake. Not one."

CLIP: Gus walking into Pollos Hermanos in yellow shirt, calm composure. 5s.

YT:
• https://youtube.com/watch?v=EXAMPLEID&t=120s — Breaking Bad S4E2 "Thirty-Eight Snub" cold open, Gus arriving at restaurant
• Backup search: "Gus Fring Pollos Hermanos entrance scene 1080p"

IMG: "Gus Fring Pollos Hermanos yellow shirt still 4K"

━━━ 2 ━━━
"He outlived the cartel that murdered his partner."

CLIP: Gus at Don Eladio's pool in Salud — toasting tequila, confident.

YT:
• https://youtube.com/watch?v=EXAMPLEID&t=1340s — Breaking Bad S4E10 "Salud" poisoning scene
• Backup search: "Breaking Bad Salud Gus tequila poisoning 4K"

IMG: "Gus Fring Don Eladio pool Salud still"

━━━ 3 ━━━
"He outlasted three DEA investigations."

CLIP: Gus at the DEA fundraiser, serving coffee to Hank and Merkert.

YT:
• https://youtube.com/watch?v=EXAMPLEID&t=1980s — Breaking Bad S3E11 "Abiquiu" DEA fundraiser
• Backup search: "Gus Fring DEA fundraiser serving coffee Breaking Bad"

IMG: "Gus Fring Hank Schrader DEA fundraiser still"

━━━ 4 ━━━
"He looked the cousins in the eye, let them walk into his territory, and waited patiently while his enemies destroyed themselves trying to reach him."

CLIP: The cousins walking through desert in cold open, silent, slow advance.

YT:
• https://youtube.com/watch?v=EXAMPLEID&t=0s — Breaking Bad S3E1 "No Más" or S3E3 cousins cold open
• Backup search: "Breaking Bad cousins walking desert cold open 4K"

IMG: "Breaking Bad Salamanca cousins desert still"

━━━ 5 ━━━
"He was the most controlled antagonist in modern television."

CLIP: Hold on Gus's composed boardroom face, static frame.

YT:
• https://youtube.com/watch?v=EXAMPLEID&t=1620s — Breaking Bad S4E1 "Box Cutter" lab inspection composed face
• Backup search: "Gus Fring composed face Box Cutter scene"

IMG: "Gus Fring close up composed portrait still 4K"

━━━ 6 ━━━
"And then, in his final scene, he walked into a nursing home alone, sat down across from a paralyzed old man, and got himself killed."

CLIP: Wide of Casa Tranquila exterior, then Gus walking corridor alone.

YT:
• https://youtube.com/watch?v=EXAMPLEID&t=2100s — Breaking Bad S4E13 "Face Off" Casa Tranquila arrival
• Backup search: "Breaking Bad Face Off Casa Tranquila Gus arrives nursing home"

IMG: "Casa Tranquila nursing home Breaking Bad still"

━━━ 7 ━━━
"Why?"

CLIP: Cut to black, 1 beat hold.

IMG: Not needed — black frame only.

━━━ 8 ━━━
"Because of the only thing Gus Fring could never control — his hatred for Hector Salamanca. This is the scene where Gus Fring finally lost control. And every detail of it was planned by Walter White."

CLIP: Three quick cuts — Gus's face, Hector ringing bell, Walter watching from parking lot.

YT:
• https://youtube.com/watch?v=EXAMPLEID&t=2340s — Breaking Bad S4E13 "Face Off" nursing home sit-down
• https://youtube.com/watch?v=EXAMPLEID&t=180s — Breaking Bad S4E13 "Face Off" Walter in parking lot

IMG: "Walter White car surveillance Face Off Breaking Bad still"
```

---

## QUALITY BENCHMARKS

1. **One line = one block.** No merging unrelated lines.
2. **Lead with YT URL + timestamp** when web search is available. Otherwise canonical reference + search query.
3. **One image query.** Not three.
4. **No emotional function / camera behavior / color grade per line.** That's locked in Phase 1.
5. **No confidence rating unless genuinely low** (then a single ⚠️ with a one-line reason).
6. **No fluff opener.** Output starts with the first `━━━ 1 ━━━` block.
7. **Max ~8 lines per block.** If you're writing more, you're over-explaining.

---

## NOTES ON URLs IN THIS EXAMPLE

The URLs shown use `EXAMPLEID` as a placeholder. When you run this on a platform with live web search (Grok, ChatGPT with browsing, Gemini with grounding, Claude with web search), the AI will return actual verified YouTube video IDs and timestamps. Without web search, it will fall back to canonical scene references + search queries.
