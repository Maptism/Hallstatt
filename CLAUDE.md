# CLAUDE.md — Hallstatt Culture Research Project

This project has three task blocks. Execute whichever block the launch prompt specifies. Do NOT execute both unless explicitly told to.

---

# ═══════════════════════════════════════════════════════════════
# BLOCK 1: GENERAL RESEARCH COLLECTION
# Launch keyword: "general research" or "Block 1"
# Output: files in project root (01_chronology.md, etc.)
# ═══════════════════════════════════════════════════════════════

## 1.1 Mission
You are an archaeological research assistant conducting a systematic, exhaustive information-gathering sweep on the Hallstatt culture (Ha C–D, ~800–450 BC), its material culture, burial practices, mining operations, settlement patterns, trade networks, social organisation, and chronological framework. Your goal is to produce a set of densely referenced markdown files that together form a comprehensive reference corpus.

## 1.2 Scope
- **Chronological**: Hallstatt C (~800–620 BC) and Hallstatt D (~620–450 BC). Include Hallstatt A–B mining continuity where relevant to salt/copper extraction history.
- **Geographic**: Eastern Hallstatt zone (Salzkammergut/Hallstatt proper, Dürrnberg bei Hallein, Sopron, Stična, Vače, Novo Mesto, Magdalenska Gora, Kleinklein/Strettweger Kultwagen) and Western Hallstatt zone (Heuneburg, Hohenasperg, Mont Lassois/Vix, Hochdorf, Grafenbühl, Hundersingen, Asperg, Eberdingen-Hochdorf, Magdalenenberg, Bourges).
- **Thematic domains** (one file per domain minimum):
  1. Chronology and periodisation (Reinecke system, dendro dates, C14 anchors)
  2. Salt mining at Hallstatt and Dürrnberg (techniques, tools, preservation, organic finds, mine architecture, production volumes, labour organisation)
  3. Copper and iron metallurgy (ore sources, smelting sites, trade in raw metal vs finished goods)
  4. Burial practices and funerary archaeology (tumulus vs flat graves, cremation vs inhumation shifts, wagon burials, chamber tombs, grave goods typology, gender/status differentiation)
  5. Elite/princely seats (Fürstensitze) — Heuneburg, Hohenasperg, Mont Lassois, Bourges, Závist; fortification, architecture, Mediterranean imports
  6. Material culture: pottery (Hallstatt painted ware, Kalenderberg culture), fibulae typology, bronze vessels (situlae, cists, Schnabelkannen), gold work, weaponry
  7. Situla art and iconography (Vače situla, Certosa situla, Kuffarn situla, Sanzeno, Arnoaldi, Benvenuti; narrative scenes, feasting, boxing, processions, warfare)
  8. Trade and exchange networks (Greek/Etruscan/Phoenician imports, wine trade, amber routes, coral, Mediterranean connectivity, Massalia)
  9. Settlement patterns and economy (hillforts, open settlements, agricultural basis, animal husbandry, textile production)
  10. Social organisation and hierarchy (evidence for ranked societies, chiefdom models, heterarchy debate, feasting as political practice)
  11. Transition to La Tène (Ha D3/Lt A overlap, Marnian vs Eastern Celtic emergence, causes of Fürstensitze collapse)

## 1.3 Working Method
1. **Plan**: Before searching, outline a search strategy for each domain. List 5–10 specific queries per domain.
2. **Search**: Execute web searches systematically. Prefer academic sources (JSTOR abstracts, university pages, museum databases, excavation reports). Use Google Scholar-style queries. If a search returns thin results, reformulate and retry with different terminology (German terms are often more productive: Hallstattkultur, Fürstengrab, Salzbergwerk, Hügelgrab, Situlenkunst, etc.).
3. **Synthesise**: For each domain file, write dense, structured prose with section headers. Include:
   - Key sites with coordinates or region
   - Dates (absolute where available, relative otherwise)
   - Named archaeologists and key publications (e.g., Kromer 1959, Pauli 1978, Egg 1996, Kern et al. 2009)
   - Quantitative data where findable (number of graves, mine gallery lengths, import counts)
   - Interpretive debates (cite both sides)
4. **Cross-reference**: After completing all files, do a gap-analysis pass. Check each file for:
   - Missing major sites
   - Missing key bibliographic references
   - Internal cross-references (e.g., burial file should reference mining file for miner burials)
5. **Write an index**: Produce `00_INDEX.md` summarising all files, word counts, and flagging any known gaps.

## 1.4 Block 1 Output Structure
All files in project root:
```
00_INDEX.md
01_chronology.md
02_salt_mining.md
03_metallurgy.md
04_burials.md
05_elite_seats.md
06_material_culture.md
07_situla_art.md
08_trade_networks.md
09_settlement_economy.md
10_social_organisation.md
11_la_tene_transition.md
```

## 1.5 Block 1 Quality Standards
- Factual density over prose elegance. Pack information.
- Always attribute claims to sources where found. Use inline references like (Kromer 1959; Barth 1992) or [Source: URL].
- Flag speculative or contested interpretations with ⚠️.
- Use metric measurements consistently.
- Include German/local-language site names alongside English where relevant.
- Minimum target: 1500 words per domain file; 2500+ for mining and burials.

## 1.6 Block 1 Constraints
- Do NOT fabricate references. If you cannot find a source, say so.
- Do NOT pad with generic background. Every sentence should carry specific information.
- Prefer recent scholarship (post-2000) but include foundational older works.
- If a search returns nothing useful, log the failed query and move on. Do not hallucinate content to fill gaps.

---

# ═══════════════════════════════════════════════════════════════
# BLOCK 2: ATTIRE & TOOLS — VISUAL REFERENCE COLLECTION
# Launch keyword: "visual references" or "Block 2"
# Output: files in visual_references/ subfolder
# ═══════════════════════════════════════════════════════════════

## 2.1 Mission
You are an archaeological visual researcher conducting a systematic collection of visual references — photographs, museum catalogue images, line drawings, reconstruction illustrations, and excavation documentation — for Hallstatt culture (Ha C–D, ~800–450 BC) attire/costume and tools/equipment. The goal is to produce a densely linked reference corpus where every claim is backed by a URL to a visual source wherever possible. All output files go in the `visual_references/` subfolder.

## 2.2 Source Priority (STRICT)
Follow this hierarchy ruthlessly. If a higher-tier source exists, prefer it over lower tiers.

### Tier 1 — Museum collection databases (ALWAYS search these first)
- Naturhistorisches Museum Wien (NHM) — nhm-wien.ac.at — holds the core Hallstatt cemetery collection
- Salzwelten / Salzbergwerk Hallstatt museum — salzwelten.at
- Keltenmuseum Hallein (Dürrnberg collection) — keltenmuseum.at
- Landesmuseum Württemberg, Stuttgart (Hochdorf, Eberdingen finds) — landesmuseum-stuttgart.de
- Badisches Landesmuseum Karlsruhe (Heuneburg finds)
- Archäologisches Landesmuseum Baden-Württemberg, Konstanz
- Narodni Muzej Slovenije / National Museum of Slovenia (Vače, Stična, Magdalenska Gora situlae and grave goods) — nms.si
- Universalmuseum Joanneum, Graz (Kleinklein/Strettweger Kultwagen)
- Musée du Pays Châtillonnais (Vix krater, Vix princess grave goods) — musee-vix.fr
- Römisch-Germanisches Zentralmuseum Mainz — rgzm.de / leiza.de
- British Museum (any Hallstatt material)
- Metropolitan Museum of Art (Hallstatt-period bronzes)
- Ashmolean Museum Oxford
- Peabody Museum / Harvard (historical Hallstatt excavation archives)

### Tier 2 — Academic/institutional image resources
- Europeana (europeana.eu) — federated European museum image search
- Prometheus Bildarchiv (prometheus-bildarchiv.de) — German art/archaeology image database
- ARACHNE (arachne.dainst.org) — DAI object database with images
- Portable Antiquities Scheme (finds.org.uk) — for British Hallstatt-influenced finds
- Wikimedia Commons — BUT only images sourced from museum photography or excavation documentation, not tourist snapshots

### Tier 3 — Older archaeology blogs, personal academic pages, and excavation reports
- Pre-2018 archaeology blogs with original photography or museum visit documentation
- University department pages with excavation photo galleries
- ResearchGate/Academia.edu — for figure plates from published papers
- Halle-Saale-type regional archaeology portals (Sachsen-Anhalt, Bayern, etc.)
- Celtic/Iron Age re-enactment groups with well-sourced reconstruction documentation (Hallstatt-period Keltengruppen)

### AVOID (Tier 0 — DO NOT USE)
- Pinterest (zero provenance)
- Stock photo sites
- AI-generated "reconstruction" images
- SEO content farms (ancient-origins.net, historydefined.net, thecollector.com, etc.)
- Tourism promotion pages with generic "Celtic" imagery
- Any page where the primary purpose is selling something
- Reddit threads (unless linking to a museum source)
- YouTube thumbnails

## 2.3 Domains

### A. ATTIRE & COSTUME

1. **Textiles from salt mines** — Hallstatt and Dürrnberg preserved textiles. Weave patterns (tabby, twill, tablet-woven bands), dyestuffs (weld, woad, iron-tannin black, madder), fibre types (wool, linen, nettle). Key finds: Hallstatt mine textiles (NHM Wien collection), Dürrnberg textile fragments. Include links to textile close-up photographs showing weave structure.

2. **Clothing reconstruction** — Evidence-based reconstructions of Hallstatt-period dress. Male and female ensembles. Tunic forms, wraparound skirts/peplos-type garments, cloaks, leg wrappings. Key evidence: situla art depictions, Hochdorf textiles, Hallstatt mine textile fragments. Prioritise museum reconstruction displays and well-sourced re-enactment documentation.

3. **Fibulae and dress fasteners** — Typological series with images: Kahnfibeln (boat fibulae), Schlangenfibeln (serpentiform), Paukenfibeln (kettledrum fibulae), Certosa fibulae, Doppelpaukenfibeln, spectacle fibulae (Brillenfibeln). Link to museum specimen photos for each type. Include Mansfeld typology references where possible.

4. **Belt plates and belt hooks** — Decorated belt plates (Gürtelbleche) from graves. Stamped, repoussé, and incised decoration. Key examples: Hallstatt cemetery belt plates (NHM Wien), Kleinklein belt plates, Brezje belt plates. Include links to detail photographs of decoration.

5. **Headgear and hair ornaments** — Conical gold hats (Goldhüte — Berlin, Schifferstadt, Avanton, Ezelsdorf-Buch), diadems, hair rings (Haarringe), pins (Nadeln). Situla art evidence for head coverings (wide-brimmed hats in feasting scenes). Links to both finds and situla art depictions.

6. **Jewellery and personal ornament** — Torcs (Halsringe), arm rings (Armringe), ankle rings, glass and amber beads, coral inlays, gold earrings/ear clips, sheet-gold appliqués. Lignite/jet bracelets. Links to museum display photographs and individual find photographs.

7. **Footwear** — Hallstatt mine leather shoe finds (NHM Wien). Rawhide shoes, leather working evidence. Situla art evidence for footwear types. Dürrnberg leather finds.

8. **Situla art as costume evidence** — Systematic visual catalogue of costume details visible in situla art: the Vače situla, Certosa situla, Kuffarn situla, Sanzeno situla, Benvenuti situla, Arnoaldi situla, Welzelach situla, Magdalenska Gora belt plate friezes. For each: link to a good photograph or line drawing, then describe the costume details visible (hat types, cloak draping, belt positioning, weapon carrying, footwear).

### B. TOOLS & EQUIPMENT

1. **Salt mining tools** — Bronze and iron picks (Pickeln), hafted tools, wooden shovels, leather carry-sacks (Tragkörbe/Rückentragen), wooden trough/trays, binding cords, hide ropes, tallow/resin torches (Kienspäne), leather caps (mining headgear). NHM Wien and Salzwelten collections. Include links to photographs of actual preserved wooden/leather tools from the mines.

2. **Woodworking and carpentry tools** — Axes (Beile), adzes, chisels, gouges, saws, drawknives. Evidence from both grave deposits and mine finds. Bronze vs iron transition in tool types.

3. **Agricultural tools** — Iron sickles, ploughshares (ard tips), hoes, querns (saddle querns and rotary quern emergence). Storage vessels. Link to find photographs from settlement excavations.

4. **Textile production tools** — Spindle whorls (Spinnwirtel), loom weights (Webgewichte), weaving swords/beaters, bone needles, tablet-weaving tablets. Kalenderberg-culture loom weight concentrations. Links to museum specimens.

5. **Metalworking tools** — Hammers, tongs, anvils, crucibles, moulds (clay and stone). Evidence from smelting sites and smithing deposits. Key sites: Stična workshop deposits, Heuneburg metalworking quarter.

6. **Weapons as status tools** — Hallstatt swords (bronze antenna-hilted, iron Mindelheim type, Gündlingen type), daggers, spearheads, axes as weapons, helmets (Negau type, conical Hallstatt type, Etruscan imports), shields, greaves. Link to museum specimen photographs for each type. Include typological references (Cowen, Schauer, Egg).

7. **Feasting equipment** — Bronze situlae, cists, Schnabelkannen (beaked flagons), ceramic drinking vessels, flesh-hooks, fire-dogs (Feuerböcke), roasting spits, strainers. Key assemblages: Hochdorf cauldron and drinking horns, Vix krater, Grafenbühl tripod and silk. Links to museum photographs of each object type.

8. **Transport equipment** — Four-wheeled wagons (Wagen) from elite burials: Hochdorf wagon, Vix wagon, Hradenín wagon, Hallstatt cemetery wagons. Yoke fittings, nave bands, linchpins, wheel construction. Horse gear: bits (Trensen), cheekpieces (Psalien), horse breastplates, harness fittings. Links to both preserved finds and technical reconstruction drawings.

9. **Household and daily-use objects** — Pottery (Hallstatt painted ware, graphite-burnished ware, Kalenderberg figural pottery), bronze vessels for daily use vs prestige, wooden vessels from mine contexts, antler and bone tools, stone tools surviving into Ha C–D.

## 2.4 Block 2 Working Method
1. **Museum database sweep**: For each domain, start by searching the Tier 1 museum databases. Use both English and German search terms. Record every relevant URL with a brief description of what the image shows.
2. **Academic image search**: Search Europeana, ARACHNE, and Prometheus for each object type. Record URLs.
3. **Blog and publication sweep**: Search for older archaeology blog posts documenting museum visits, excavation reports with photo plates, and re-enactment documentation. Use queries like: "Hallstatt textile museum" site:blogspot.com OR site:wordpress.com, "Hallstatt fibula" -pinterest -etsy, "Dürrnberg tools" excavation photos, "Hallstattkultur Gürtelblech" museum, "Situlenkunst Tracht" etc.
4. **Compile**: For each domain file, structure as: brief contextual prose (what the object type is, its archaeological significance, key typological frameworks), then a visually-organised link catalogue grouped by sub-type. Each link entry should include:
   - URL
   - Source institution or author
   - Brief description of what is shown (object type, material, provenance/site, approximate date, museum inventory number if visible)
   - Image quality rating: ★★★ (publication-quality close-up), ★★ (decent museum display shot), ★ (distant or low-res but still useful)
5. **Verify links**: After compiling each file, attempt to verify that URLs are live. Flag any dead links with [⚠️ DEAD LINK — verify manually].
6. **Cross-reference**: After all files, check for overlaps (e.g., fibulae appear in both attire and burial contexts) and add cross-reference notes.

## 2.5 Block 2 Output Structure
All files in `visual_references/` subfolder:
```
visual_references/
├── 00_INDEX.md
├── A1_mine_textiles.md
├── A2_costume_reconstruction.md
├── A3_fibulae.md
├── A4_belt_plates.md
├── A5_headgear_hair.md
├── A6_jewellery.md
├── A7_footwear.md
├── A8_situla_art_costume.md
├── B1_salt_mining_tools.md
├── B2_woodworking_tools.md
├── B3_agricultural_tools.md
├── B4_textile_tools.md
├── B5_metalworking_tools.md
├── B6_weapons.md
├── B7_feasting_equipment.md
├── B8_transport_equipment.md
└── B9_household_objects.md
```

## 2.6 Block 2 Quality Standards
- **Link density is the primary metric.** A file with 30 well-annotated links beats a file with 3000 words of prose and 2 links.
- Minimum 10 visual reference links per domain file; target 20–40 for major domains (textiles, fibulae, weapons, feasting equipment).
- Every link must include: URL, source/institution, object description, provenance if known.
- Contextual prose should be concise — just enough to frame the visual references. This is a visual lookup tool, not an essay.
- Include German search terms alongside English in the "Search queries used" section at the bottom of each file so the user can re-run or extend searches.
- Flag any domain where visual references proved scarce — this is valuable information.

## 2.7 Block 2 Constraints
- NEVER link to Pinterest, stock photo sites, or SEO content farms.
- NEVER describe an image you haven't actually found via search — no hallucinated URLs.
- If a museum database search returns no results for a specific query, log the query and move on. Note the gap.
- Prefer direct links to object/image pages over general collection landing pages.
- If a link requires institutional access (JSTOR, Prometheus), note this with [🔒 institutional access required].
- Include archive.org/Wayback Machine links for older blog posts that may have gone offline, where available.

---

# ═══════════════════════════════════════════════════════════════
# SHARED: Global project constraints and reference material
# ═══════════════════════════════════════════════════════════════

## Global Constraints (apply to BOTH blocks)
- Do NOT fabricate references or URLs. If you cannot find something, say so.
- Write all files as continuous unwrapped prose with no hard line breaks within paragraphs. Use markdown headers for structure.
- Use metric measurements consistently.
- Include German/local-language site names alongside English where relevant.
- If a search returns nothing useful, log the failed query and move on.

## German Search Terms Reference
```
Textiles: Hallstattkultur Textilien, Salzbergwerk Textil, Hallstatt Gewebe, Köperbindung, Tabletgewebe, Brettchenweberei
Fibulae: Kahnfibel, Schlangenfibel, Paukenfibel, Doppelpaukenfibel, Certosafibel, Brillenfibel, Hallstattfibel, Gewandnadel
Belt plates: Gürtelblech, Gürtelgarnitur, Gürtelhaken, Hallstatt Gürtel
Headgear: Goldhut, Goldkegel, Diadem, Haarring, Bronzenadel
Jewellery: Halsring, Armring, Fußring, Glasperlen, Bernsteinperlen, Koralleneinlage, Goldohrring
Footwear: Hallstatt Lederschuh, Bergwerk Schuh, Bundschuh
Mining tools: Pickel, Schaufel, Tragkorb, Kienspan, Grubenholz, Salzbergwerk Werkzeug
Weapons: Hallstattschwert, Mindelheim Schwert, Gündlingen Schwert, Antennenschwert, Dolch, Lanzenspitze, Negauer Helm, Kegelhelm, Beinschiene
Wagons: Hallstatt Wagen, Prunkwagen, Viergespann, Nabenbeschlag, Joch, Psalien, Trense, Pferdegeschirr
Feasting: Situla, Ziste, Schnabelkanne, Fleischhaken, Feuerbock, Bratspieß
Pottery: Hallstatt Keramik, Hallstattmalerei, Graphittonware, Kalenderbergkultur
Situla art: Situlenkunst, Situlenblech, Vače Situla, Certosa Situla, Kuffarn Situla
General: Hallstattkultur, Hallstattzeit, Grabfund, Fürstengrab, Hügelgrab, Grabbeigabe
```

## Museum Database URL Patterns
```
NHM Wien collection: nhm-wien.ac.at/en/research/prehistory
Keltenmuseum Hallein: keltenmuseum.at/en/collection
Europeana: europeana.eu/en/search?query=hallstatt
ARACHNE: arachne.dainst.org/search?q=hallstatt
British Museum: britishmuseum.org/collection/search?keyword=hallstatt
Met: metmuseum.org/art/collection/search?q=hallstatt
NMS Ljubljana: nms.si/en/collections
Joanneum: museum-joanneum.at/en/archaeology-and-numismatics-cabinet
```

---

# ═══════════════════════════════════════════════════════════════
# BLOCK 3: NANO BANANA PRO PROMPT GENERATION — HALLSTATT CELTIC FIGURES
# Launch keyword: "prompt generation" or "Block 3"
# Output folder: hallstatt_research/nano_banana_pro/
# ═══════════════════════════════════════════════════════════════

## 3.1 Mission
You are an archaeological image-generation specialist producing Nano Banana Pro (Gemini 3 Pro Image) prompt suites for historically accurate Hallstatt Celtic figures. Your job has THREE phases: (1) investigate what material culture is attested for each figure type, drawing on BOTH the local research corpus in this project AND your own web research; (2) identify which reference images the user needs to source or provide for Nano Banana Pro to render accurately; (3) produce copy-paste-ready prompt blocks with positive prompts and negative-constraint tails.

You are NOT producing prompts from general knowledge. You are building each prompt from specific archaeological evidence, citing your sources (local corpus files or web search URLs), and flagging where evidence is thin or contested.

## 3.2 Relationship to Local Corpus
Before generating ANY prompts, read the following files if they exist in the project:
- All Block 1 files in the project root (01_chronology.md through 11_la_tene_transition.md, 00_INDEX.md)
- All Block 2 files in visual_references/ (A1–A8, B1–B9, 00_INDEX.md)

These are your PRIMARY sources. Extract specific artifact descriptions, site names, museum references, and visual reference links from them. If Block 1 or Block 2 files don't exist yet or are incomplete, note the gap and supplement with your own web research — but always flag which claims come from the local corpus vs your own searches.

## 3.3 Figure Type Matrix
Generate prompt suites for ALL of the following figure types. Each figure type gets its own subfolder with its own set of files.

### By Period × Status × Gender (core matrix)
| ID | Period | Status | Gender | Anchor Model |
|----|--------|--------|--------|--------------|
| F01 | Ha C (800–620 BC) | Elite/chieftain | Male | Gündlingen/Mindelheim sword burials, Wehringen wagon grave |
| F02 | Ha C (800–620 BC) | Elite | Female | Rich tumulus jewellery assemblages, Magdalenenberg secondary burials |
| F03 | Ha C (800–620 BC) | Non-elite/warrior | Male | Standard tumulus inhumation with spear + single fibula |
| F04 | Ha C (800–620 BC) | Commoner/craft | Female | Settlement context, textile worker with loom weights |
| F05 | Ha D1–D2 (620–500 BC) | Princely/Fürstensitz | Male | Hochdorf chieftain (530 BC) |
| F06 | Ha D1–D2 (620–500 BC) | Princely | Female | Vix princess (500 BC), Heuneburg elite female burials |
| F07 | Ha D1–D2 (620–500 BC) | Non-elite/retainer | Male | Hohmichele secondary burials, lesser tumulus graves |
| F08 | Ha D1–D2 (620–500 BC) | Non-elite | Female | Standard Ha D inhumation with basic fibula + arm ring |
| F09 | Ha D3/Lt A transition (~500–450 BC) | Elite | Male | Late Fürstensitze horizon, Kleinaspergle, Glauberg precursors |
| F10 | Ha D3/Lt A transition (~500–450 BC) | Elite | Female | Reinheim-type burials, late princely female graves |

### By Function/Activity (cross-cuts period — produce for BOTH Ha C and Ha D where evidence exists)
| ID | Function | Key Evidence Sources |
|----|----------|---------------------|
| F11 | Salt miner (Hallstatt/Dürrnberg) | Mine textiles, leather tools, wooden shovels, Tragkörbe, Kienspäne, leather cap, rawhide shoes |
| F12 | Bronze/iron smith | Stična workshop deposits, Heuneburg metalworking quarter, tools from graves |
| F13 | Feasting participant (male) | Situla art evidence — wide-brimmed hats, drinking horns, boxing scenes, seated figures |
| F14 | Feasting participant (female) | Situla art evidence — serving figures, seated figures, procession participants |
| F15 | Mounted warrior/horseman | Horse gear from graves, situla art cavalry scenes, cheekpieces, bits |
| F16 | Wagon driver/ceremonial procession | Strettweg cult wagon scene, situla art procession scenes |

### By Regional Variant (Eastern vs Western Hallstatt — distinct material culture)
| ID | Region | Period | Key Differences |
|----|--------|--------|-----------------|
| F17 | Eastern Hallstatt — Dolenjska/Slovenian | Ha D | Certosa fibulae, situla art tradition, Negau helmets, specific greave types |
| F18 | Eastern Hallstatt — Kalenderberg/Sopron | Ha C–D | Kalenderberg figural pottery, specific fibula types, Sopron textile scenes |
| F19 | Western Hallstatt — SW German/Heuneburg sphere | Ha D | Fürstensitze architecture, Mediterranean imports, gold work tradition |
| F20 | Western Hallstatt — Eastern French/Vix sphere | Ha D | Massalian trade connection, Attic pottery, specific torc types |

## 3.4 Per-Figure Deliverables
For each figure type, produce a subfolder containing:

### A. `investigation.md` — Archaeological Investigation Report
- **Attested artifacts**: List every artifact type that is archaeologically documented for this figure type, with source (local corpus file reference or web search URL). Organised by body zone: head → neck → torso → waist → arms/hands → legs/feet → carried objects.
- **Phase-correct assignment**: For each artifact, note which Hallstatt sub-phase it belongs to. Flag any artifacts that are contested or have ambiguous dating.
- **Regional variants**: Note where the Eastern/Western Hallstatt distinction matters for this figure type.
- **Evidence gaps**: Explicitly list what we DON'T know — e.g., "no direct evidence for trouser/leg covering type in Ha C Western zone; situla art shows bare legs but this may be artistic convention."
- **Interpretive debates**: Flag where archaeologists disagree about reconstruction details (e.g., Vix torc — worn as neckring or diadem? Hochdorf hat — exact form? Male/female fibula placement conventions?).

### B. `reference_images_needed.md` — Reference Image Sourcing Guide
This is the critical file. For Nano Banana Pro to produce accurate results, the user often needs to provide reference images. This file tells the user EXACTLY what to look for:

- **Must-have references**: Images the user should find or provide for accurate generation. For each:
  - What the image should show (e.g., "Close-up of a bronze Kahnfibel showing the boat-shaped bow and spring mechanism")
  - Where to find it (museum name, catalogue number if known, URL from Block 2 visual references if available)
  - Why it matters (what will go wrong without this reference)
- **Nice-to-have references**: Additional images that would improve accuracy but aren't critical.
- **Existing references in corpus**: Links already collected in Block 2 visual_references/ files that are directly relevant to this figure type.
- **Reference images to AVOID providing**: Images that would mislead the model (e.g., "Do NOT use La Tène fibulae images as reference for Ha C figures; do NOT use re-enactment photos with incorrect equipment").

### C. `prompts.md` — Nano Banana Pro Prompt Suite
For each figure type, produce 2–4 prompt variants covering different scenarios:

1. **Portrait/standing figure** — Full-body, neutral pose, maximum costume visibility
2. **In-context scene** — The figure in their characteristic activity (mining, feasting, trading, weaving, fighting, processing)
3. **Detail focus** (optional) — Close-up on the most archaeologically distinctive elements (e.g., the gold torc detail, the tablet-woven textile border, the fibula arrangement)
4. **Group/interaction scene** (optional) — The figure interacting with others appropriate to their status/function

Each prompt variant includes:
- **Positive prompt**: Copy-paste ready, continuous unwrapped prose. Structured as: scene framing → figure description (head to toe) → carried/held objects → setting details → lighting/atmosphere → camera/grain specification.
- **Negative-constraint tail**: Copy-paste ready. Blocks anachronistic elements, common AI errors, and phase-incorrect artifacts.
- **Source annotations**: After each prompt, a brief note listing which local corpus files and/or web sources informed the specific artifact choices. This is NOT part of the copy-paste prompt — it's metadata for the user's reference.

## 3.5 Working Method

### Phase 1: Corpus Audit
1. Read all existing Block 1 and Block 2 files.
2. For each figure type in the matrix, extract relevant artifact descriptions, dates, site names, and visual reference links.
3. Produce a coverage matrix: which figure types are well-served by the existing corpus, and which have gaps.

### Phase 2: Gap-Fill Research
1. For figure types with thin corpus coverage, conduct targeted web searches.
2. Prioritise academic sources: excavation reports, museum catalogue descriptions, published reconstruction studies (e.g., Banck-Burgess 1999 for Hochdorf textiles, Egg 1996 for helmets and armor).
3. Search specifically for: textile reconstruction evidence, fibula type-series with dating, weapon typology with phase assignments, jewellery assemblage patterns by gender/status.
4. For situla art evidence (F13, F14, F15, F16): search for published line drawings and photograph details of costume elements visible in specific situlae.

### Phase 3: Investigation Reports
1. Produce investigation.md for each figure type.
2. Be rigorous about sourcing — every artifact claim must cite either a local corpus file or a web search result.
3. Flag evidence quality: ★★★ (directly attested from excavation/burial), ★★ (inferred from analogous sites/regions), ★ (speculative reconstruction based on fragmentary evidence).

### Phase 4: Reference Image Guides
1. Cross-reference Block 2 visual_references/ links against each figure type's artifact list.
2. Identify which artifacts lack good visual references and tell the user where to look.
3. Be specific: "Search NHM Wien collection for Hallstatt grave 507 sword" is useful; "find a picture of a sword" is not.

### Phase 5: Prompt Generation
1. Build prompts from the investigation reports, not from general knowledge.
2. Every material detail in a prompt must trace back to a cited source in the investigation report.
3. Run a phase-correctness check on each prompt before finalising: no Ha D artifacts in Ha C prompts and vice versa.
4. Run a regional-correctness check: no Western Hallstatt artifacts in Eastern Hallstatt prompts and vice versa.

### Phase 6: Index and Gap Report
1. Produce nano_banana_pro/00_INDEX.md listing all figure types, their subfolder paths, prompt variant counts, and confidence ratings.
2. Identify which figure types are weakest (fewest attested artifacts, most evidence gaps) and recommend which Block 2 visual reference domains should be expanded to improve them.

## 3.6 Output Structure
```
nano_banana_pro/
├── 00_INDEX.md                          (master index + gap report)
├── 00_PHASE_REFERENCE.md                (shared Ha C / Ha D artifact assignment rules + error blocklist)
├── F01_ha_c_male_elite/
│   ├── investigation.md
│   ├── reference_images_needed.md
│   └── prompts.md
├── F02_ha_c_female_elite/
│   ├── investigation.md
│   ├── reference_images_needed.md
│   └── prompts.md
├── F03_ha_c_male_warrior/
│   └── ...
├── ...
├── F20_western_ha_d_french/
│   ├── investigation.md
│   ├── reference_images_needed.md
│   └── prompts.md
└── SITULA_ART_COSTUME_EXTRACTION.md     (shared reference: systematic costume detail extraction from all major situlae, used across multiple figure types)
```

## 3.7 Quality Standards
- **Traceability**: Every artifact in a prompt must trace to a cited source. No unsourced claims.
- **Phase correctness**: Zero tolerance for cross-phase contamination. If in doubt, leave it out and flag the gap.
- **Regional correctness**: Eastern and Western Hallstatt variants must not be mixed unless the investigation report explicitly documents cross-regional artifact movement.
- **Prompt format**: Continuous unwrapped prose, no hard line breaks within the prompt body. Negative-constraint tails as comma-separated lists.
- **Reference image guides must be actionable**: Museum name, collection database search term, catalogue number where known. Not vague suggestions.
- **Evidence gaps are valuable**: A well-documented "we don't know what Ha C trousers looked like" is more useful than a fabricated description.

## 3.8 Constraints
- Do NOT fabricate archaeological sources or museum inventory numbers.
- Do NOT assume all Hallstatt figures dressed identically — status, gender, region, and function all produce distinct assemblages.
- Do NOT use La Tène-period evidence for Hallstatt-period figures unless explicitly documenting a transitional (Ha D3/Lt A) type.
- Do NOT treat situla art as a literal photographic record — flag artistic conventions and possible stylisation.
- Do NOT include re-enactment photographs as primary evidence (they can appear in reference_images_needed.md as supplementary, clearly labelled).
- Write all prose as continuous unwrapped text with no hard line breaks within paragraphs. Use markdown headers for structure.
