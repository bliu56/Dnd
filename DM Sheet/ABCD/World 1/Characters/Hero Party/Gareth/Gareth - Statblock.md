```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Gareth Holt — The Wall"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 18
hp: 140
hit_dice: "16d10 + 48"
speed: "30 ft."
stats: [16, 14, 20, 10, 10, 12]
saves:
  - str: "+5"
  - con: "+8"
skillsaves:
  - athletics: "+8"
  - intimidation: "+4"
damage_resistances: "bludgeoning, piercing, slashing from nonmagical attacks"
condition_immunities: "frightened"
senses: "passive Perception 10"
languages: "Common, one noble dialect"
cr: "7"
traits:
  - name: "Supernatural Endurance"
    desc: "Gareth reduces all incoming damage by 4."
  - name: "Immovable"
    desc: "Gareth cannot be knocked prone or forcibly moved unless the effect deals more than 30 damage in a single hit."
  - name: "Iron Retaliation (Recharge 5–6)"
    desc: "When Gareth is hit by a melee attack, he can use his reaction to absorb the blow. His next Warhammer attack before the end of his next turn deals an additional 1d10 for every 5 points of damage received."
  - name: "Holt's Stand"
    desc: "Gareth wields a heavy warhammer passed down the second sons of House Holt, inscribed with the motto 'We do not fall.' Grants +2 to attack and damage rolls. Anchoring Strike: reduces a Large or smaller target's speed by 10 ft until the start of Gareth's next turn. On a hit against a prone creature, it cannot stand up until the end of Gareth's next turn. Unfallen Resolve: for every 10 damage Gareth has taken since last knocked prone, the hammer deals an additional 1d4 bludgeoning damage (max +4d4)."
actions:
  - name: "Multiattack"
    desc: "Gareth makes two Warhammer attacks and one Shield Bash."
  - name: "Warhammer"
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 1d8+5 bludgeoning (1d10+5 two-handed), plus additional damage from Holt's Stand's Unfallen Resolve trait."
  - name: "Shield Bash"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 1d6+3 bludgeoning. The target must make a DC 14 Strength save or be knocked prone and pushed 10 ft."
  - name: "Holt's Advance (Recharge 5–6)"
    desc: "Gareth charges up to 20 ft in a straight line. Each creature in his path makes a DC 14 Strength save, taking 4d8+3 bludgeoning damage and being knocked prone on a failure, or half damage on a success."
bonus_actions:
  - name: "Anchored"
    desc: "Gareth slams the butt of his warhammer into the ground. Spectral chains burst from the impact point. Until the start of his next turn: he cannot be moved by any means. Each creature of his choice within 10 ft must make a DC 14 Strength save or be pulled up to 5 ft toward him. Creatures within 10 ft of Gareth cannot take the Disengage action."
reactions:
  - name: "Rebuff"
    desc: "When a creature within 5 ft hits Gareth with a melee attack, he can make one Shield Bash against them as a reaction."
  - name: "Hold the Line"
    desc: "When an ally within 5 ft would be hit by an attack, Gareth can redirect the attack to himself instead and move his ally 5 ft without provoking opportunity attacks."
```
