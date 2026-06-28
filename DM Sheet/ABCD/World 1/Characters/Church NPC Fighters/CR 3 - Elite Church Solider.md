```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Elite Church Soldier"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 17
hp: 65
hit_dice: "10d8 + 20"
speed: "30 ft."
stats: [16, 12, 15, 11, 12, 10]
saves:
  - str: "+5"
  - con: "+4"
skillsaves:
  - athletics: "+5"
  - perception: "+3"
senses: "passive Perception 13"
languages: "Common"
cr: "3"
traits:
  - name: "Disciplined Formation"
    desc: "While within 5 ft. of at least one allied soldier, this soldier has advantage on attack rolls and cannot be flanked."
  - name: "Zealous Response"
    desc: "When this soldier starts its turn with no allied soldiers within 30 ft. and no conscious superior officer, it deals an extra 4 (1d8) damage on all weapon attacks that turn as it fights for its life."
  - name: "Interlocking Shields"
    desc: "While this soldier is within 5 ft. of at least one other soldier with this trait, all soldiers in the formation gain a +1 bonus to AC and have advantage on saving throws against spells and effects that target an area."
actions:
  - name: "Multiattack"
    desc: "The soldier makes two Longsword attacks."
  - name: "Longsword"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) when wielded with two hands."
  - name: "Shield Slam"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4 + 3) bludgeoning damage. The target must make a DC 13 Strength save or be knocked prone. If the target is already prone, it takes an additional 4 (1d8) bludgeoning damage."
  - name: "Coordinated Push"
    desc: "The soldier and one allied soldier within 5 ft. each make a Shield Slam against the same target. If both hit, the target is pushed 10 ft. and knocked prone with disadvantage on the save."
reactions:
  - name: "Cover the Gap"
    desc: "When an allied soldier within 5 ft. is reduced to 0 HP, this soldier can move up to 5 ft. into the space they vacated without provoking opportunity attacks."
  - name: "Faithful Sacrifice"
    desc: "When Crane uses his Rosary of Shared Burden to transfer damage to this soldier, this soldier can use its reaction to reduce that damage by 5 (1d10) — the rosary's bead glows white-hot for an instant as the soldier endures."
```
