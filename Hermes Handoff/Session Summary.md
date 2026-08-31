# Hermes — Session Handoff

> Read this first on a new session to pick up where I left off.

**Last session:** Saturday, July 22, 2026

---

## Constraints
- Ask before writing/overwriting any file. Never assume yes.
- "eos" = write this handoff and stop.

## Statblock Format
- Saves and skillsaves use flat YAML mapping with plain numbers (e.g. `str: 9` not `- str: "+9"`) — renderer auto-adds the + sign. Applied to [[Tristan]]'s statblock.

## What Was Worked On

### Demon King Baal (Tristan) — Act 3
- Split lore from statblock into two files:
  - `Tristan (Act 3).md` — background, personality, Will stages (flavor), Corruption, fighting style
  - `Tristan - Statblock.md` — full CR 12 statblock in statblock syntax, matching Hero Party format
- Fixed saves format (used `str: 9` instead of `- str: "+9"` to avoid `++9` rendering)
- **On hold:** Planning 3-stage boss phases (Stage 1 Sealed → Stage 2 Awakened → Stage 3 Oblivion) — waiting for images.

### World 2 — Player Vote Pitches
- Created player-facing pitches for 3 world options in `Idea Workshop.md`:
  - **Mystery** — Single city, looming threat, ticking clock. Regression loop hidden from players.
  - **Hunt** — Kingdom beast hunt, rival parties, contained expeditions. Prep + intel matter as much as fighting.
  - **War** — Asymmetric, outmatched, guerrilla tactics against a brilliant commander.
- Rough DM notes kept above the player-facing section (separated by `---`).

### NPC Soundboard
- Created `hero-party-soundboard.json` in `World 1/Church/` with base64-embedded portraits for Kael, Isolde, Seraphine, Gareth.
- `World 1/Demon/` folder exists but is empty — ready for a demon soundboard JSON.

### Key Party Status
- Traveling with Ash toward the Demon King.
- Hero Party is NOT with them.
- Darrin is with them — can borrow/enhance spells, possibly half-demon.

## Open / Next to Write
- Tristan 3-stage boss forms (on hold, waiting for images)
- Demon faction NPC soundboard JSON
- Fallowmere, Hearthfen, Corrupted Treant's Lair, Healer's Hut, Twin Peaks, Demon Encampment, Rogue Demon Cell, Ashen Vale
- Pranav's shadow creature
- Fishing quest, The Unlit warlock subclass
- testing
