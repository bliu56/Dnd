```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Kael Dawnborne — The Hero"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 17
hp: 120
hit_dice: "16d10 + 32"
speed: "30 ft."
stats: [16, 12, 14, 12, 12, 16]
saves:
  - str: "+6"
  - con: "+5"
  - cha: "+6"
skillsaves:
  - athletics: "+6"
  - intimidation: "+6"
  - persuasion: "+6"
  - history: "+4"
damage_resistances: "radiant"
condition_immunities: "frightened"
senses: "passive Perception 9"
languages: "Common, one noble dialect"
cr: "8"
traits:
  - name: "Divine Blessing"
    desc: "The divine power of the Hero title enhances Kael beyond his natural capability. While active: +4 to all ability scores (buffed: 20/16/18/16/16/20), +2 to all saves, +10 ft speed (40 ft). HP increases to 152 (16d10+64). He regains 20 HP at the start of each turn. All damage taken is halved before any other calculation. Resistance to ranged weapon damage. Immune to magic missile. Spell attack rolls against him have disadvantage. Immune to frightened, charmed, paralyzed, stunned, poisoned, and exhaustion. Once per turn on a melee hit, deals an additional 2d12 radiant damage and automatically crits."
  - name: "Legendary Resistance (1/Day)"
    desc: "If Kael fails a saving throw, he can choose to succeed instead."
actions:
  - name: "Multiattack"
    desc: "Kael makes two Longsword attacks."
  - name: "Longsword"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 1d10+3 slashing damage. Until the start of Kael's next turn, the target has disadvantage on opportunity attacks against him."
  - name: "Holy Lance"
    desc: "Ranged Spell Attack: +6 to hit, range 90 ft., one target. Hit: 3d6 radiant damage. The target must make a DC 15 Constitution save or be blinded until the end of its next turn."
  - name: "Divine Punishment (Recharge 5–6)"
    desc: "Kael channels divine power at one creature within 60 ft. The target makes a DC 15 Wisdom save, taking 6d8 radiant damage on a failure or half on a success."
  - name: "Divine Barrage (Recharge 5–6)"
    desc: "Kael raises his sword and holy energy rains down in a 15 ft radius centered on a point within 60 ft. Each creature in the area makes a DC 15 Dexterity save, taking 8d6 radiant damage on a failure or half on a success."
bonus_actions:
  - name: "Unbothered Advance"
    desc: "Kael moves up to 15 ft toward a creature without provoking opportunity attacks and makes one Longsword attack."
  - name: "Divine Pressure"
    desc: "One creature within 5 ft must make a DC 15 Strength save or be knocked prone. If they fail, Kael immediately makes one Longsword attack against them with advantage (crit on 19-20)."
reactions:
  - name: "Divine Grace"
    desc: "When a creature hits or misses Kael with a melee attack, a pulse of divine energy strikes the attacker for 2d8 radiant damage."
```
