```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Crane — Captain of the Faithful"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 19
hp: 112
hit_dice: "15d8 + 45"
speed: "30 ft."
stats: [18, 12, 16, 14, 12, 14]
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
cr: "6"
traits:
  - name: "Tactical Command"
    desc: "At the start of each of Crane's turns, one ally within 30 ft. that he can see can use their reaction to make one weapon attack or move up to half their speed. Crane must be conscious for this trait to function."
  - name: "Unyielding"
    desc: "Crane cannot be frightened and will not willingly move more than 60 ft. from his current position during combat. He does not retreat."
  - name: "Formation Leader"
    desc: "Allied soldiers within 15 ft. of Crane have advantage on saving throws against being frightened or charmed."
  - name: "Rosary of Shared Burden — Aegis of the Faithful"
    desc: "While Crane can see three or more conscious allied Church soldiers within 30 ft., he can transfer any damage he would take to one of those soldiers of his choice instead. The soldier takes the full damage. Crane takes none. If fewer than three allied soldiers are within range, this trait does not function."
  - name: "Rosary of Shared Burden — Weakpoint"
    desc: "If Crane takes 30 or more damage from a single hit or spell, the excess spills over and Crane takes it directly. If all nearby soldiers are killed within the same turn, the Rosary has no one to transfer to and Crane becomes vulnerable."
  - name: "Rosary of Shared Burden — The Shepherd's Mercy (1/Day)"
    desc: "As an action, Crane grips his rosary and speaks a prayer. The wounded are forced upright — eyes snapping open, bodies moving before they are fully aware. On a living creature: touch a creature. It regains 4d8 + 6 hit points. On a dead creature (within 1 minute): touch the creature. It revives with 1 hit point — gasping awake as the Church's magic drags them back."
actions:
  - name: "Multiattack"
    desc: "Crane makes two Longsword attacks."
  - name: "Longsword"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) when wielded with two hands."
  - name: "Shield Bash"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 6 (1d4 + 4) bludgeoning damage. The target must make a DC 14 Strength save or be knocked prone."
  - name: "Rally (1/Day)"
    desc: "Crane calls out to all allies within 60 ft. Each ally regains 2d6 + 3 temporary HP and can immediately move up to 10 ft. without provoking opportunity attacks."
reactions:
  - name: "Hold the Line"
    desc: "When an ally within 5 ft. would be hit by an attack, Crane can use his reaction to impose disadvantage on that attack roll."
```
