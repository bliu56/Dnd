```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "The Fragment"
size: "Large"
type: "fiend (shapeless)"
alignment: "unaligned"
ac: 14
hp: 105
hit_dice: "10d10 + 50"
speed: "30 ft., climb 30 ft."
stats: [17, 15, 20, 5, 13, 7]
saves:
  - dex: "+5"
  - con: "+8"
  - wis: "+4"
skillsaves:
  - perception: "+1"
damage_resistances: "cold, necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
damage_immunities: "poison, psychic"
condition_immunities: "charmed, frightened, paralyzed, poisoned, prone"
senses: "blindsight 30 ft. (blind beyond this radius), darkvision 120 ft., passive Perception 11"
languages: "understands Infernal but cannot speak or communicate in any way"
cr: "7"
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
  - name: "Innate Spellcasting"
    desc: "The fragment can innately cast the following spells, requiring no components: 1/day each: darkness, fear."
actions:
  - name: "Multiattack"
    desc: "The fragment makes two Tendril Lash attacks."
  - name: "Tendril Lash"
    desc: "Melee Weapon Attack: +7 to hit, reach 15 ft., one target. Hit: 15 (3d6 + 5) slashing damage. If the target is Medium or smaller, it must succeed on a DC 15 Strength saving throw or be grappled (escape DC 15). The fragment can grapple up to two creatures at once."
  - name: "Engulf"
    desc: "The fragment engulfs one creature it is grappling. The target is blinded, restrained, and unable to breathe, taking 9 (2d8) necrotic damage at the start of each of its turns. A creature within 5 feet can take an action to pull the engulfed creature out with a DC 15 Strength check, ending the condition."
  - name: "Shriek of the Severed (Recharge 5–6)"
    desc: "The fragment emits a sound felt more than heard. Each creature within 20 feet that the fragment perceives as a threat must make a DC 13 Wisdom saving throw. On a failure: 16 (3d10) psychic damage and frightened for 1 minute. On a success: half damage, not frightened."
reactions:
  - name: "Protective Surge"
    desc: "When the Ward takes damage from a creature the fragment perceives as hostile, the fragment can move up to its full speed toward that creature without provoking opportunity attacks."
```
