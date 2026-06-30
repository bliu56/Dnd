```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Ser Aldous Crane"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 18
hp: 102
hit_dice: "12d8 + 48"
speed: "30 ft."
stats: [18, 12, 16, 14, 13, 14]
saves:
  - str: "+7"
  - con: "+6"
skillsaves:
  - athletics: "+7"
  - intimidation: "+5"
  - perception: "+4"
  - history: "+5"
senses: "passive Perception 14"
languages: "Common"
cr: "5"
traits:
  - name: "Tactical Command"
    desc: "At the start of each of Crane's turns, one ally within 30 ft that he can see can use their reaction to make one weapon attack or move up to half their speed. Crane must be conscious."
  - name: "Unyielding"
    desc: "Crane cannot be frightened and will not willingly move more than 60 ft from his current position during combat. He does not retreat."
  - name: "Formation Leader"
    desc: "Allied soldiers within 15 ft of Crane have advantage on saves against being frightened or charmed."
  - name: "Martyrs' Reliquary"
    desc: "While Crane has allied soldiers alive within 30 ft, any damage he takes is instead dealt to one of those soldiers of his choice. The soldier takes the full damage. Additionally, as a bonus action, Crane can activate the reliquary to imbue a fallen or unconscious ally within 30 ft with holy resolve — that ally immediately stands with 1 HP (if at 0), their eyes glowing faintly white, and they can act normally on their next turn. An ally raised this way crumbles to ash after 1 minute or when they drop to 0 HP again — they are already dead, and the reliquary is merely delaying their rest."
actions:
  - name: "Multiattack"
    desc: "Crane makes two Longsword attacks. He may replace one attack with Shield Bash."
  - name: "Longsword"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 1d8+4 slashing (1d10+4 two-handed)."
  - name: "Shield Bash"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 1d4+4 bludgeoning. The target must make a DC 14 Strength save or be knocked prone."
  - name: "Rally (1/Day)"
    desc: "Crane calls out to all allies within 60 ft. Each ally regains 1d6+2 temp HP and can immediately move up to 10 ft without provoking opportunity attacks."
reactions:
  - name: "Hold the Line"
    desc: "When an ally within 5 ft would be hit by an attack, Crane imposes disadvantage on that attack roll."
```
