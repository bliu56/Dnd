```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Isolde Crane — The Arbiter"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 14
hp: 84
hit_dice: "13d8 + 26"
speed: "30 ft."
stats: [9, 13, 14, 13, 19, 16]
saves:
  - wis: "+7"
  - cha: "+6"
skillsaves:
  - insight: "+7"
  - medicine: "+10"
  - persuasion: "+6"
  - religion: "+7"
damage_resistances: "radiant"
senses: "passive Perception 14"
languages: "Common, Celestial, one noble dialect"
cr: "6"
traits:
  - name: "Goddess's Vessel"
    desc: "Isolde has advantage on all saving throws against spells and magical effects."
  - name: "Empowered Healing"
    desc: "When Isolde restores HP to a creature, they regain an additional 1d8 HP."
  - name: "Spellcasting"
    desc: "Isolde is a 9th level divine spellcaster (Wisdom, spell save DC 15, +7 to hit). Cantrips: Sacred Flame, Guidance, Spare the Dying, Toll the Dead. 1st (4 slots): Healing Word, Cure Wounds, Bless, Command. 2nd (3 slots): Lesser Restoration, Prayer of Healing, Aid, Silence. 3rd (3 slots): Mass Healing Word, Revivify, Dispel Magic. 4th (3 slots): Death Ward, Guardian of Faith, Banishment. 5th (1 slot): Mass Cure Wounds, Flame Strike."
  - name: "Sacred Blessing"
    desc: "At the start of each of Isolde's turns, she generates 1 stack of Sacred Favor (max 6). As a bonus action, she can distribute stacks among up to 4 allies. Each stack grants +1 to attack rolls and saving throws, and +1d4 to healing received until the start of Isolde's next turn. Undistributed stacks carry over."
actions:
  - name: "Multiattack"
    desc: "Isolde makes two Sorin's Light attacks or casts one cantrip twice."
  - name: "Aelura's Light"
    desc: "Ranged Spell Attack: +7 to hit, range 60 ft., one target. Hit: 2d8 radiant damage (3d8 if the target is frightened)."
  - name: "God's Authority (3/Day)"
    desc: "Isolde calls upon one of the gods she serves. Each invocation can only be used once per day. Calder's Renewal: one creature within 30 ft regains 3d8+4 HP and has advantage on their next saving throw. Sorin's Charge: up to 3 allies within 30 ft gain 10 temp HP and immunity to all conditions for 1 minute. Vessa's Binding: one creature within 60 ft, DC 15 CHA save. Bound by an oath for 1 minute. Violation deals 3d10 psychic damage and ends. Aelura's Verdict: one creature within 60 ft, DC 15 WIS save. 6d8 radiant damage, revealed (invisibility/transformations/illusions within 30 ft suppressed 1 round). Half on save. Lirien's Mercy: a creature reduced to 0 HP within the last minute is restored to 1 HP and all conditions end. Fails if Isolde has judged them unworthy."
  - name: "Divine Descent (1/Day)"
    desc: "For 3 turns, Isolde gains: fly speed 60 ft, unlimited God's Authority invocations, Aelura's Light deals +1d8 radiant, regenerates 10 HP/turn, immune to frightened and charmed, and gains access to The Final Verdict: a pillar of divine light in a 30 ft radius within 60 ft. Each creature makes a DC 15 Con save, taking 10d8 radiant on a failure or half on a success. Creatures of Isolde's choice are unaffected. After 3 turns, Isolde drops to 0 HP and stabilizes after 1 minute."
bonus_actions:
  - name: "Healing Word (4/Day)"
    desc: "One worthy ally within 60 ft regains 1d6+4 HP."
reactions:
  - name: "Protective Grace"
    desc: "When a worthy ally within 30 ft is hit by an attack, Isolde imposes disadvantage on the attack roll."
```
