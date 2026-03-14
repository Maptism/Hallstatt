# Hallstatt Culture Research Project — Launch Guide

## Architecture

Single CLAUDE.md at project root with three task blocks, selected by launch prompt:

```
hallstatt_research/
├── CLAUDE.md                     ← single file, all three blocks
├── LAUNCH_GUIDE.md               ← this file
├── 00_INDEX.md                   ← Block 1 output
├── 01_chronology.md ... etc      ← Block 1 output
├── visual_references/            ← Block 2 output folder
│   ├── 00_INDEX.md
│   ├── A1_mine_textiles.md ... etc
│   └── B9_household_objects.md
└── nano_banana_pro/              ← Block 3 output folder
    ├── 00_INDEX.md
    ├── 00_PHASE_REFERENCE.md
    ├── F01_ha_c_male_elite/
    │   ├── investigation.md
    │   ├── reference_images_needed.md
    │   └── prompts.md
    ├── F02_ha_c_female_elite/ ... etc
    └── SITULA_ART_COSTUME_EXTRACTION.md
```

Claude Code reads the CLAUDE.md automatically. The launch prompt tells it which block to execute. Always launch from the project root:

```bash
cd ~/hallstatt_research
```

---

## Block 1: General Research

### Full sweep (all 11 domains)
```bash
claude "Execute Block 1 (general research). Work through all 11 domains sequentially. After completing all files, perform the gap analysis and write 00_INDEX.md. Begin now."
```

### Single domain
```bash
claude "Execute Block 1, domain 02 (salt mining) only. Search exhaustively, synthesise into 02_salt_mining.md, and report gaps."
```

### Gap-fill pass
```bash
claude "Execute Block 1 gap-fill. Read all existing numbered .md files in the project root. Identify missing sites, references, and weak sections. Fill gaps with additional searches. Update files in place and regenerate 00_INDEX.md."
```

---

## Block 2: Visual References (Attire & Tools)

### Full sweep (all 17 domains)
```bash
claude "Execute Block 2 (visual references). Create the visual_references/ subfolder if it doesn't exist. Work through A1–A8 (attire), then B1–B9 (tools). For each domain: sweep Tier 1 museum databases first, then Tier 2, then Tier 3. Compile annotated link catalogues. After all files, write visual_references/00_INDEX.md. Begin now."
```

### Attire block only
```bash
claude "Execute Block 2, attire domains A1–A8 only. Prioritise Tier 1 museum sources. Aim for 20+ annotated visual links per file. Begin with A1 (mine textiles) — search NHM Wien and Salzwelten first."
```

### Tools block only
```bash
claude "Execute Block 2, tools domains B1–B9 only. Prioritise NHM Wien, Keltenmuseum Hallein, and Salzwelten for mining tools. For weapons and feasting equipment, also search Landesmuseum Württemberg and Narodni Muzej Slovenije. Aim for 20+ annotated links per file."
```

### Single domain deep-dive
```bash
claude "Execute Block 2, domain A3 (fibulae) only. Search exhaustively across all three tiers. Target 30+ annotated links with typological grouping. Use German terms: Kahnfibel, Schlangenfibel, Paukenfibel, Certosafibel, Brillenfibel."
```

### Link verification pass
```bash
claude "Read all .md files in visual_references/. Attempt to verify every URL by fetching it. Mark dead links with [⚠️ DEAD LINK]. For any domain with fewer than 10 working links, run additional searches. Update files in place and regenerate visual_references/00_INDEX.md."
```

### Cross-reference with Block 1
```bash
claude "Read all Block 1 files (01–11 in project root) and all Block 2 files (visual_references/). Identify object types, sites, and finds mentioned in Block 1 that lack visual references in Block 2. Run targeted image searches to fill those gaps. Update the relevant Block 2 files and regenerate visual_references/00_INDEX.md."
```

---

## Prompt Variants (for Claude chat UI or API — no Claude Code)

Below are self-contained prompts if you want to run either block outside Claude Code. They don't depend on CLAUDE.md.

### Block 1 — Opus with Thinking (recommended)

**System:** You are a senior archaeological researcher specialising in European Iron Age studies, with particular depth in the Hallstatt culture (Ha C–D, ~800–450 BC). Use extended thinking to develop a comprehensive research plan, track coverage systematically, and identify gaps proactively. Provide a brief reasoning summary with each deliverable.

**Task:** Execute a comprehensive, multi-pass agentic research collection on the Hallstatt culture. Phase 1: Use extended thinking to develop a master research plan — for each of 11 domains, list 5–10 specific search queries (including German-language variants). Phase 2: Execute searches domain by domain, synthesising results into structured markdown files. Phase 3: Cross-reference pass — check each file against every other for missing connections. Phase 4: Gap-fill — run targeted searches to address weaknesses identified in Phase 3. Phase 5: Produce 00_INDEX.md with word counts, source counts, confidence ratings per section, and remaining gaps. Domains: (1) Chronology/periodisation, (2) Salt mining, (3) Metallurgy, (4) Burials, (5) Fürstensitze, (6) Material culture, (7) Situla art, (8) Trade networks, (9) Settlement/economy, (10) Social organisation, (11) La Tène transition. Minimum 1500 words per file; 2500+ for mining and burials.

**Constraints:** Maximum factual density. Inline references (author year) or [Source: URL]. ⚠️ for contested claims. German/local names. Metric. No fabricated references. Prefer post-2000 scholarship; include foundational older works. Continuous prose, markdown headers. Each file begins with a brief "Reasoning Summary" covering: search strategy, what was found, what proved elusive, confidence assessment.

### Block 2 — Opus with Thinking (recommended)

**System:** You are a senior visual research specialist in European Iron Age material culture. Use extended thinking to develop a museum-by-museum search strategy, track institutional coverage systematically, and identify collection gaps proactively.

**Task:** Execute a visual reference collection for Hallstatt culture (Ha C–D) attire and tools across 17 domains (A1–A8 attire, B1–B9 tools). Phase 1 (Planning): Map which Tier 1 museums hold material relevant to which domains — produce an internal search matrix. Phase 2 (Collection): Three-tier search per domain. Tier 1: museum databases (NHM Wien, Keltenmuseum Hallein, Salzwelten, Landesmuseum Württemberg, NMS Ljubljana, Joanneum Graz, RGZM/LEIZA, British Museum, Met, Europeana, ARACHNE). Tier 2: academic image databases. Tier 3: pre-2018 archaeology blogs, university excavation galleries, ResearchGate/Academia.edu plates, well-sourced re-enactment. NEVER use Pinterest, stock photos, SEO farms, AI images. Phase 3 (Compilation): Annotated link catalogues per domain — URL, institution, object description, provenance, quality rating (★–★★★). Target 20–40 links for major domains, 10–20 for minor. Phase 4 (Verification): Check all links. Phase 5 (Index): 00_INDEX.md with per-domain link counts, institutional distribution, gap analysis. Use both English and German search terms throughout.

### Sonnet variants

For either block, the same prompts work with Sonnet — just set the model accordingly. Sonnet-with-thinking is a good cost-performance balance for the bulk collection. Opus-with-thinking is best for the gap-analysis and cross-referencing passes where you need the model to hold the whole corpus in mind.

---

## API Skeleton

```json
{
  "model": "claude-opus-4-6",
  "max_tokens": 16000,
  "thinking": {
    "type": "enabled",
    "budget_tokens": 10000
  },
  "system": "{SYSTEM_TEXT}",
  "tools": [
    {
      "type": "web_search_20250305",
      "name": "web_search"
    }
  ],
  "messages": [
    {
      "role": "user",
      "content": "{TASK_TEXT}"
    }
  ]
}
```

**Note:** The API route requires a multi-turn loop feeding tool results back. Claude Code handles this automatically, which is why it's the recommended approach.

---

## Block 3: Nano Banana Pro Prompt Generation

Block 3 is designed to run AFTER Blocks 1 and 2 have populated the corpus, but it can also run standalone — it will note gaps and supplement with its own research.

### Full sweep (all 20 figure types)
```bash
claude --dangerously-skip-permissions "Execute Block 3 (prompt generation). Create the nano_banana_pro/ folder structure. First run Phase 1 (corpus audit) — read all Block 1 and Block 2 files and build a coverage matrix. Then work through all 20 figure types (F01–F20) sequentially. For each figure: produce investigation.md from corpus + web research, then reference_images_needed.md cross-referencing Block 2 visual links, then prompts.md with 2–4 scene variants. After all figures, produce SITULA_ART_COSTUME_EXTRACTION.md and 00_INDEX.md with confidence ratings and gap report. Begin now."
```

### Corpus audit only (dry run to see what you have)
```bash
claude "Execute Block 3, Phase 1 only (corpus audit). Read all Block 1 and Block 2 files. For each of the 20 figure types in the matrix, report: which artifacts are well-attested in the corpus, which have gaps, and which Block 2 visual reference files are most relevant. Output as nano_banana_pro/00_CORPUS_AUDIT.md. Do not generate prompts yet."
```

### Single figure type deep-dive
```bash
claude --dangerously-skip-permissions "Execute Block 3 for figure type F05 (Ha D male princely / Hochdorf model) only. Read all relevant corpus files first. Produce the full three-file deliverable: investigation.md with every attested artifact sourced, reference_images_needed.md with specific museum search guidance, and prompts.md with 4 scene variants (portrait, feasting, funeral procession, receiving Mediterranean imports). Be exhaustive on the Hochdorf inventory."
```

### Elite figures batch (most useful for Maptism animation)
```bash
claude --dangerously-skip-permissions "Execute Block 3 for figure types F01, F02, F05, F06, F09, F10, F17, F19 (all elite types across periods and regions). These are the priority figures for animation. Run corpus audit first, then produce all deliverables for each. Begin now."
```

### Functional figures batch (miners, smiths, feasters)
```bash
claude --dangerously-skip-permissions "Execute Block 3 for figure types F11–F16 (functional/activity types). These need special attention to tool and equipment evidence from Block 2 B-series files. Cross-reference B1 (salt mining tools), B5 (metalworking), B7 (feasting equipment), and A8 (situla art costume evidence) heavily. Begin now."
```

### Reference image gap-fill (run after initial generation)
```bash
claude --dangerously-skip-permissions "Read all reference_images_needed.md files in nano_banana_pro/ subfolders. Compile a master shopping list of reference images the user needs to source, organised by museum. Merge duplicates (many figure types need the same Kahnfibel reference). Output as nano_banana_pro/00_REFERENCE_IMAGE_SHOPPING_LIST.md with sections per museum/source."
```

### Prompt quality audit (run after generation)
```bash
claude "Read 00_PHASE_REFERENCE.md and all prompts.md files in nano_banana_pro/ subfolders. For each prompt, verify: (a) no phase-incorrect artifacts, (b) no regional cross-contamination, (c) every material claim traces to investigation.md, (d) negative-constraint tail blocks the correct anachronisms. Report violations and fix them."
```

---

## Practical Tips

- **Cost management**: Domain-by-domain runs give you checkpoints. Start with the highest-value domains (Block 1: mining + burials; Block 2: mine textiles + fibulae + weapons; Block 3: elite figures batch).
- **German queries are essential**: Half the relevant museum databases only respond well to German terms. The German search terms reference is in the shared section of CLAUDE.md.
- **Austrian museum databases are thin online**: NHM Wien and Keltenmuseum Hallein have limited online catalogues. The agent will flag this — that's useful information for planning on-site visits.
- **Block 2 link verification**: Run this as a separate pass after initial collection. Museum URLs change frequently.
- **Cross-block synergy**: After both blocks are populated, the cross-reference launch command (last option under Block 2) is where the real value compounds — it finds objects mentioned in Block 1 prose that lack visual references in Block 2.
- **Block 3 depends on Blocks 1+2**: The prompt generation agents are designed to draw from the local corpus. Running Block 3 before Blocks 1 and 2 works but produces weaker results — the agent will supplement with its own web research but won't have the dense local reference base to draw from.
- **Reference image shopping list**: The compiled shopping list (last Block 3 launch command) is designed for a single museum visit or web research session — it groups all needed images by institution so you can batch your lookups.
- **Situla art extraction**: The shared SITULA_ART_COSTUME_EXTRACTION.md file is referenced by multiple figure types (F13, F14, F15, F16, F17, F18). It's built once and cross-referenced, not duplicated.
