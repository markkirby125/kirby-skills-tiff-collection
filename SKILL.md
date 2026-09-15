---
name: kirby-skills-tiff-collection
description: "Use when routing PLR personalisation, Voice DNA, audience intel, or storyline-bank work across the Tiffany Lambert suite."
category: helper
triggers: [kirby-tiff, tiff-collection, plr-skills, tiff-plr, plr-suite]
---

# Tiffany Lambert PLR Skills Collection

A master catalog and navigation hub for all 8 specialised **Kirby PLR Skills** designed for the Google Antigravity, Claude Code, Cursor, and Windsurf agent ecosystems.

These skills enforce strict, deterministic standard operating procedures (SOPs) to execute the Two-Way Personalization & Framework Fusion system across raw PLR text, completely eliminating generic AI slop.

Read the sibling `SKILL.md` named below. Do not guess. `framework-fusion` belongs to `kirby-plr-personalizer`, not this catalog.

---

## Master Skills Index

| # | Skill | Category | Primary Triggers | Description |
|---|---|---|---|---|
| 1 | [**kirby-voice-dna-extractor**](../kirby-voice-dna-extractor/SKILL.md) | Profiling | `voice-dna`, `author-voice` | Reverse-engineers author voice, cadence, and lexicon into machine-enforceable Voice DNA profiles. |
| 2 | [**kirby-audience-intel-profiler**](../kirby-audience-intel-profiler/SKILL.md) | Profiling | `audience-intel`, `buyer-persona-intel` | Extracts subniche jargon, operational friction, and taboo buzzwords to ground AI content in buyer reality. |
| 3 | [**kirby-storyline-bank**](../kirby-storyline-bank/SKILL.md) | Storytelling | `storyline-bank`, `extract-stories` | Extracts, structures, and catalogs personal business scars and epiphanies for authentic storytelling. |
| 4 | [**kirby-plr-personalizer**](../kirby-plr-personalizer/SKILL.md) | Execution | `personalize-plr`, `framework-fusion` | Master Two-Way PLR Personalization & Framework Fusion engine for AI agents. |
| 5 | [**kirby-plr-email-sequences**](../kirby-plr-email-sequences/SKILL.md) | Repurposing | `plr-to-email`, `email-autoresponder-plr` | Converts raw informational PLR into high-converting direct-response email autoresponder sequences. |
| 6 | [**kirby-plr-sales-converter**](../kirby-plr-sales-converter/SKILL.md) | Repurposing | `plr-to-sales-page`, `vsl-from-plr` | Transforms educational PLR into persuasive direct-response sales copy across commercial delivery models. |
| 7 | [**kirby-plr-omnichannel-repurposer**](../kirby-plr-omnichannel-repurposer/SKILL.md) | Repurposing | `repurpose-plr`, `content-cascade` | Deconstructs a single personalized PLR asset into 12 platform-native social, audio-visual, and editorial formats. |
| 8 | [**kirby-plr-diagnostic-debugger**](../kirby-plr-diagnostic-debugger/SKILL.md) | Quality | `audit-plr`, `content-doctor` | 15-point diagnostic audit and surgical repair suite to eliminate tone drift, forced stories, and AI slop. |

### Canonical datasets

Fusion reads these three files only (create via the matching extractor if missing):

| File | Producer |
|---|---|
| `voice_dna.yaml` | `kirby-voice-dna-extractor` |
| `audience_profile.yaml` | `kirby-audience-intel-profiler` |
| `storyline_bank.json` | `kirby-storyline-bank` |

---

## Quick Invocation Guide
- To list all Kirby skills: use `/kirby`.
- To execute a PLR workflow, prompt with a child trigger (e.g., `personalize-plr`, `voice-dna`, `storyline-bank`).
