# prose-drafts: Manuscript Production (`SUBVERTED_HARRY`)

[![Repo Type: Narrative Manuscript](https://img.shields.io/badge/Repo-Prose%20Drafts-gold.svg)](https://github.com/ImmortalWiz/prose-drafts)
[![Standard: Clean Text Only](https://img.shields.io/badge/Standard-Clean%20Manuscript%20Only-brightgreen.svg)](https://github.com/ImmortalWiz/prose-drafts)
[![Parent Engine](https://img.shields.io/badge/Parent-harry--potter--and--the--magical--reality--check-blue.svg)](https://github.com/ImmortalWiz/harry-potter-and-the-magical-reality-check)

The **Prose Drafts (`prose-drafts`)** repository houses the clean, publishable narrative manuscript for all volumes of `SUBVERTED_HARRY`. It is the final output of the entire five-stage pipeline.

---

## 🚫 The Golden Rule of Prose Drafts

> **ZERO META-ANNOTATIONS. ZERO AUTHOR NOTES. ZERO INLINE PROGRAMMING TAGS.**

Files in this repository must read like published literary fiction. 
* Do **not** include `[Author's Note]`, `[Scene Break: Check Ledger]`, or meta-commentary inside manuscript files.
* All architectural notes, blocking, and subtext belong in [`scene-blueprints`](https://github.com/ImmortalWiz/scene-blueprints).
* All character state tracking belongs in [`war-entities`](https://github.com/ImmortalWiz/war-entities).

---

## 📂 Manuscript Directory Structure

```
prose-drafts/
├── book_01_the_fame_shield/
│   ├── ch01_the_cleansing_of_number_four.txt   # Opening: The quiet horror of Privet Drive and Vesselist cleansing
│   ├── ch02_the_boy_with_the_gilded_smile.txt  # Diagon Alley: The birth of the Lockhart persona
│   └── ch03_the_first_glaive_of_gawain.txt     # The Hogwarts Express and the first cracks in the facade
└── book_05_the_hollow_victory/
    └── ch14_smoke_over_whitehall.txt           # The brutal climax of the guerrilla war
```

---

## 🖋️ Lexical, Tonal & Sensory Guidelines

1. **Visceral, Grounded Prose:**
   * Ground descriptions in sensory weight: the cold sting of well-water on chapped hands, the chemical smell of cheap polish, the oppressive suburban silence of Privet Drive.
   * Avoid purple prose, melodramatic villain monologues, and video-game style spell casting announcements.
2. **Harry's Duality:**
   * **External:** Tailored robes, radiant smiles, practiced witty repartee, dodging technical questions by turning them into jokes or theatrical bows.
   * **Internal:** Cold panic, hyper-vigilance, memorizing escape routes, terror that someone will notice he doesn't know basic first-year theory.
3. **The Dursley Tone:**
   * Treat Petunia's silence with absolute literary gravity. She does not scream; she adjusts curtains, scrubs counters until her knuckles are white, and looks through Harry as though he were made of clear glass.
   * Marge's religiosity is cold, dogmatic, and bureaucratic—framed as an act of terrible moral duty.

---

## 🤖 Instructions for AI Drafting Models

1. **Prerequisite Check:** Before writing a single paragraph, you must parse:
   * The active chapter outline from `plotline-architect/`.
   * The granular scene blueprint from `scene-blueprints/`.
   * Harry's `magical_gap_ledger.md` from `war-entities/`.
2. **Output Format:** Output narrative prose strictly. Do not precede or follow the draft with conversational commentary like *"Here is the chapter you requested."*
3. **Post-Draft Regression Assertion:** Immediately after generating prose, run the continuity verification:
   * Verify no spells above Harry's ledger were cast.
   * Verify Dumbledore acts out of benevolent confirmation bias.
   * Verify tone remains psychologically authentic and free of cartoonish tropes.
