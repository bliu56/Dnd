```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "The Fragment"
size: "Large"
type: "fiend (shapeless)"
alignment: "unaligned"
ac: 16
hp: 138
hit_dice: "12d10 + 72"
speed: "30 ft., climb 30 ft."
stats: [18, 16, 22, 5, 14, 7]
saves:
  - dex: "+7"
  - con: "+10"
  - wis: "+6"
skillsaves:
  - perception: "+2"
damage_resistances: "cold, necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
damage_immunities: "poison, psychic"
condition_immunities: "charmed, frightened, paralyzed, poisoned, prone"
senses: "blindsight 60 ft. (blind beyond this radius), darkvision 120 ft., passive Perception 12"
languages: "understands Infernal but cannot speak or communicate in any way"
cr: "9"
traits:
  - name: "Bound to the Ward"
    desc: "The fragment is anchored to Pranav and cannot willingly move more than 1 mile from her. If forced beyond this range, it is banished back into dormancy within her and cannot manifest again for 24 hours."
  - name: "Broken Threat Assessment"
    desc: "The fragment cannot distinguish real threats from harmless actions. When a creature near Pranav does anything the fragment interprets as a threat (raising a weapon, shouting, moving too fast, reaching for her), the DM determines whether the fragment fixates on that creature. Once fixated, the fragment attacks that creature exclusively until it flees, falls unconscious, or the fragment is banished."
  - name: "Dormant Until Failure"
    desc: "The fragment cannot manifest while Pranav is conscious and above 0 HP. It manifests immediately when she drops to 0 HP (before death saving throws), stabilizing her automatically. At the end of combat or if Pranav is revived, the fragment retreats back into dormancy."
  - name: "Magic Resistance"
    desc: "The fragment has advantage on saving throws against spells and other magical effects."
  - name: "Severed Mind"
    desc: "Immune to any spell or effect that reads, charms, or communicates with a mind (detect thoughts, suggestion, etc.)."
  - name: "The Appetite (1/Day)"
    desc: "As a bonus action, the fragment designates one creature it can see as Prey for 1 minute. The fragment has advantage on attack rolls against that creature. Whenever it damages the Prey, it heals 1d8 HP. If the Prey drops to 0 HP, the fragment's next ability this turn restores an additional 2d8 HP."
actions:
  - name: "Multiattack"
    desc: "The fragment makes two Flesh Strike attacks, or one Flesh Strike and one special ability (Flesh Spear, Binding Flesh, or Consuming Bite)."
  - name: "Flesh Strike"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 15 (3d6 + 5) slashing damage. The wound weeps black, clotting slowly."
  - name: "Course 1 — Flesh Spear"
    desc: "Ranged spell attack, +8 to hit, 60 ft. Hit: 18 (4d8) piercing damage. The target's speed is reduced by 10 ft until the end of its next turn as it tears black-flesh shards from the wound."
  - name: "Course 2 — Binding Flesh"
    desc: "Ranged spell attack, +8 to hit, 30 ft. Hit: 10 (3d6) necrotic damage. Tendrils of shadow-flesh erupt and wrap the target's legs. The target must succeed on a DC 15 Strength save or be restrained until the end of its next turn. Can repeat the save as an action."
  - name: "Course 3 — Consuming Bite"
    desc: "The fragment's neck stretches unnaturally, its featureless head sailing forward like a serpent. Melee spell attack, +8 to hit, reach 15 ft. Hit: 14 (4d6) piercing damage. The fragment regains HP equal to half the damage dealt. The target must make a DC 15 Wisdom save or be frightened of the fragment until the end of its next turn."
  - name: "Course 3 (Alternative) — The Groundmouth"
    desc: "The fragment slams both hands into the ground. Jagged teeth erupt from the earth beneath one creature within 30 ft. The target must make a DC 15 Dexterity save. On a failure: piercing damage equal to 3d6 + 1d6 for every 10 HP the target is missing (max 6d6). On a success: half damage."
reactions:
  - name: "Protective Surge"
    desc: "When the Ward takes damage from a creature the fragment perceives as hostile, the fragment can move up to its full speed toward that creature without provoking opportunity attacks."
```
