---
layout: default
title: Prompt Generation
nav_order: 3
has_children: true
---

# 00_INDEX — Nano Banana Pro Prompt Suite: Hallstatt Celtic Figures

> **Generated:** 2026-03-14
> **Total figure types:** 20
> **Total files:** 64 (60 figure-type files + 4 shared reference files)
> **Source corpus:** Block 1 (hallstatt_research/, 11 files, ~49,595 words) + Block 2 (visual_references/, 17 files, 486 links)

---

## Coverage Matrix: Corpus Audit Summary

### Corpus Coverage by Figure Type

| ID | Figure Type | Period | Corpus Coverage | Confidence | Key Evidence Sources |
|----|-----------|--------|----------------|------------|---------------------|
| F01 | Ha C male elite/chieftain | Ha C (800–620 BC) | ★★★ Strong | HIGH | 04_burials (Mindelheim/Gündlingen swords), 06_material_culture (weapons, fibulae), B6_weapons, A3_fibulae |
| F02 | Ha C female elite | Ha C (800–620 BC) | ★★ Moderate | MEDIUM | 04_burials (ornament assemblages), A2_costume (Grömer reconstructions), A3_fibulae, A6_jewellery. Gap: no single well-preserved Ha C elite female burial equivalent to Hochdorf/Vix |
| F03 | Ha C male warrior (non-elite) | Ha C (800–620 BC) | ★★ Moderate | MEDIUM | 04_burials (Hodson tiers), 06_material_culture. Gap: non-elite graves poorly published vs princely ones |
| F04 | Ha C female craft/commoner | Ha C (800–620 BC) | ★ Thin | LOW | 09_settlement (Sopron pottery), B4_textile_tools. Gap: commoner dress almost entirely inferred; Sopron scenes = best iconographic source but limited detail |
| F05 | Ha D male princely (Hochdorf) | Ha D1–D2 (620–500 BC) | ★★★★ Excellent | VERY HIGH | 04_burials (Hochdorf detailed), 05_elite_seats, all A/B visual ref files. Best-documented figure in corpus |
| F06 | Ha D female princely (Vix) | Ha D1–D2 (620–500 BC) | ★★★★ Excellent | VERY HIGH | 04_burials (Vix), 05_elite_seats (Bettelbühl), A6_jewellery (Vix torc), B7_feasting (Vix krater) |
| F07 | Ha D male retainer | Ha D1–D2 (620–500 BC) | ★★ Moderate | MEDIUM | 04_burials (Hohmichele/Magdalenenberg secondaries). Gap: retainer-level assemblages poorly published |
| F08 | Ha D female non-elite | Ha D1–D2 (620–500 BC) | ★★ Moderate | MEDIUM | 04_burials (standard inhumations), A3_fibulae. Gap: defined largely by absence of elite items |
| F09 | Ha D3/Lt A male elite (transitional) | Ha D3 (~510–450 BC) | ★★★ Strong | HIGH | 11_la_tene_transition (Kleinaspergle, Glauberg), A3_fibulae (Certosa), B7_feasting (Schnabelkannen) |
| F10 | Ha D3/Lt A female elite (transitional) | Ha D3 (~510–450 BC) | ★★★ Strong | HIGH | 11_la_tene_transition (Reinheim), A6_jewellery (torcs) |
| F11 | Salt miner | Ha C–D (cross-period) | ★★★★ Excellent | VERY HIGH | 02_salt_mining (full treatment), A1_mine_textiles (32 links), A7_footwear (3D shoe), B1_salt_mining_tools (32 links). BEST direct evidence of any figure |
| F12 | Bronze/iron smith | Ha C–D (cross-period) | ★★ Moderate | MEDIUM | 03_metallurgy, B5_metalworking_tools (22 links). Gap: no identified "smith's burial" with diagnostic toolkit |
| F13 | Feasting participant (male) | Ha D primarily | ★★★ Strong | HIGH | 07_situla_art (Vače, Certosa), A8_situla_art_costume (38 links), B7_feasting_equipment (32 links), 10_social_organisation (Dietler feasting theory) |
| F14 | Feasting participant (female) | Ha D primarily | ★ Thin | LOW | 07_situla_art (limited female figures), Strettweg central figure. Gap: female feasting roles poorly depicted in situla art |
| F15 | Mounted warrior/horseman | Ha C–D | ★★ Moderate | MEDIUM | 07_situla_art (cavalry scenes), B8_transport (horse gear), 06_material_culture (bits, cheekpieces). Gap: horse gear published but rider costume less clear |
| F16 | Wagon driver/procession | Ha C–D | ★★ Moderate | MEDIUM | 07_situla_art (procession scenes), B8_transport (wagons), Strettweg cult wagon. Gap: "driver" as social role is reconstructed, not directly attested |
| F17 | Eastern — Dolenjska/Slovenian | Ha D | ★★★ Strong | HIGH | 04_burials (Stična, Novo Mesto, Magdalenska Gora), 05_elite_seats (Kleinklein), B6_weapons (Negau helmets, cuirasses), A4_belt_plates, A8_situla_art |
| F18 | Eastern — Kalenderberg/Sopron | Ha C–D | ★★ Moderate | MEDIUM | 06_material_culture (Kalenderberg ceramics), 09_settlement (Sopron). Gap: Sopron pottery images poorly available online |
| F19 | Western — Heuneburg sphere | Ha D | ★★★★ Excellent | VERY HIGH | 05_elite_seats (Heuneburg), 08_trade_networks (Mediterranean imports), 09_settlement (outer settlement). Richest settlement evidence in corpus |
| F20 | Western — Vix/French sphere | Ha D | ★★★ Strong | HIGH | 05_elite_seats (Mont Lassois), 04_burials (Vix), 08_trade_networks (Rhône-Saône axis) |

### Confidence Rating Key
- **VERY HIGH**: Multiple well-preserved primary sources (excavated burials with published assemblages, preserved organic finds, abundant visual references)
- **HIGH**: Good primary evidence from burials + supplementary iconographic/corpus evidence
- **MEDIUM**: Evidence exists but has significant gaps; some elements reconstructed from analogy
- **LOW**: Most elements inferred or reconstructed; direct evidence thin

---

## File Listing

### Shared Reference Files
```
nano_banana_pro/
├── 00_INDEX.md                              (this file)
├── 00_PHASE_REFERENCE.md                    (Ha C vs Ha D artifact rules + universal error blocklist)
├── 00_REFERENCE_IMAGE_SHOPPING_LIST.md      (consolidated museum reference image guide)
└── SITULA_ART_COSTUME_EXTRACTION.md         (costume evidence from all major situlae)
```

### Figure Type Subfolders (20 × 3 files = 60 files)

| ID | Subfolder | Prompt Variants | Confidence |
|----|-----------|:--------------:|:----------:|
| F01 | F01_ha_c_male_elite/ | 3 | HIGH |
| F02 | F02_ha_c_female_elite/ | 3 | MEDIUM |
| F03 | F03_ha_c_male_warrior/ | 2 | MEDIUM |
| F04 | F04_ha_c_female_craft/ | 2 | LOW |
| F05 | F05_ha_d_male_princely/ | 4 | VERY HIGH |
| F06 | F06_ha_d_female_princely/ | 4 | VERY HIGH |
| F07 | F07_ha_d_male_retainer/ | 2 | MEDIUM |
| F08 | F08_ha_d_female_nonelite/ | 2 | MEDIUM |
| F09 | F09_ha_d3_male_elite/ | 3 | HIGH |
| F10 | F10_ha_d3_female_elite/ | 3 | HIGH |
| F11 | F11_salt_miner/ | 3 | VERY HIGH |
| F12 | F12_smith/ | 3 | MEDIUM |
| F13 | F13_feasting_male/ | 3 | HIGH |
| F14 | F14_feasting_female/ | 2 | LOW |
| F15 | F15_mounted_warrior/ | 3 | MEDIUM |
| F16 | F16_wagon_driver/ | 3 | MEDIUM |
| F17 | F17_eastern_dolenjska/ | 3 | HIGH |
| F18 | F18_eastern_kalenderberg/ | 2 | MEDIUM |
| F19 | F19_western_heuneburg/ | 3 | VERY HIGH |
| F20 | F20_western_vix/ | 3 | HIGH |

Each subfolder contains:
- `investigation.md` — Archaeological investigation report (attested artifacts by body zone, evidence quality, gaps)
- `reference_images_needed.md` — Reference image sourcing guide (must-have, nice-to-have, existing Block 2 links, avoid list)
- `prompts.md` — Nano Banana Pro prompt suite (positive prompts + negative-constraint tails + source annotations)

---

## Gap Report

### Weakest Figure Types (expand these domains in Block 2 to improve)

1. **F04 (Ha C female commoner)** — Confidence LOW. Commoner dress is almost entirely inferred from negative evidence. The Sopron pottery weaving scenes are the single best source but are not available as high-quality online images. **Recommended Block 2 expansion:** Contact Soproni Múzeum for Sopron figural pottery photos; expand B4_textile_tools with loom reconstruction images.

2. **F14 (Feasting female)** — Confidence LOW. Female roles in situla art feasting scenes are subordinate/marginal. The Strettweg central female figure is the strongest evidence but is a unique ritual/mythological context, not a standard feasting participant. **Recommended Block 2 expansion:** Detailed close-ups of female figures in Vače and Certosa situlae; Strettweg central figure detail photography.

3. **F12 (Smith)** — Confidence MEDIUM but with a fundamental gap: no identified Hallstatt-period smith's burial. Evidence comes from workshop debris, not personal equipment. **Recommended Block 2 expansion:** Expand B5_metalworking_tools with experimental archaeology/reconstruction photos of bloomery furnaces and forge setups.

4. **F18 (Kalenderberg/Sopron)** — Confidence MEDIUM but severely limited by the online unavailability of Sopron pottery photographs. **Recommended Block 2 expansion:** Same as F04 — Soproni Múzeum contact is critical.

### Strongest Figure Types

1. **F05 (Hochdorf princely male)** — VERY HIGH. Near-complete evidence from a single unlooted burial. Every body zone attested with specific artifacts. The UT Austin pages + NHM Wien 3D models provide excellent visual reference coverage.

2. **F11 (Salt miner)** — VERY HIGH. Best direct organic evidence of any figure type. Preserved tools, shoes, textiles, food remains. NHM Wien Sketchfab 3D models + Block 2 coverage is strong.

3. **F19 (Heuneburg sphere)** — VERY HIGH. Most extensively excavated Fürstensitz with comprehensive publication. Mediterranean imports, craft production, settlement architecture all well-documented.

4. **F06 (Vix princely female)** — VERY HIGH. The Vix burial is spectacularly rich and well-published. Gold torc, krater, wagon all documented in Block 2.

### Cross-Cutting Gaps Affecting Multiple Figures

- **Leg coverings / trousers:** No direct evidence for Hallstatt-period trouser form. Situla art shows tight-fitting or bare legs — ambiguous. Affects F01, F03, F05, F07, F09, F13, F15, F17, F19.
- **Footwear for non-miners:** Salt mine shoes are work context. No elite or non-mine footwear survives. Hochdorf gold shoe ornaments show foot covering existed but not the shoe itself. Affects all figures except F11.
- **Hair and hairstyle:** No preserved hair from Hallstatt contexts (unlike Dürrnberg later period). Situla art shows some head detail but not hair specifically. Affects all figures.
- **Textile colour accuracy:** Dyes identified analytically (woad blue, weld yellow, tannin brown) but the EXACT appearance of Hallstatt garments as worn is unknown — colours fade, and the proportion of dyed vs undyed garments is uncertain. Affects all figures.

---

## Phase-Correctness Summary

All prompts in this collection have been validated against the rules in `00_PHASE_REFERENCE.md`:

- **Ha C figures (F01–F04):** No Mediterranean imports, no Certosa fibulae, no daggers (swords only for weapon-bearing figures), no coral inlay.
- **Ha D figures (F05–F08, F17–F20):** Daggers replace swords in western zone; Mediterranean imports present at elite level; Certosa fibulae correct in eastern zone; inhumation dominant in west.
- **Transitional figures (F09–F10):** Deliberate mix of late Hallstatt + early La Tène elements flagged.
- **Cross-period figures (F11–F16):** Phase-specific variants noted where evidence differs between Ha C and Ha D.
- **Regional figures (F17–F20):** Eastern/western artifact boundaries enforced.

---

## How to Use This Collection

1. **Select your figure type** from the matrix above based on the period, status, gender, function, or region you need.
2. **Read the investigation.md** to understand what artifacts are attested and at what confidence level.
3. **Check reference_images_needed.md** for what museum photos to source or provide to the image generation model.
4. **Copy the positive prompt** from prompts.md directly into Nano Banana Pro / Gemini 3 Pro Image.
5. **Copy the negative-constraint tail** into the negative prompt field.
6. **Provide reference images** from the must-have list where available.
7. **Validate** any modifications against `00_PHASE_REFERENCE.md` before generating.
