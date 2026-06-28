```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Gorrath, the Faceless Warden"
size: "Large"
type: "fiend (demon knight)"
alignment: "lawful evil"
ac: 20
hp: 119
hit_dice: "14d10 + 42"
speed: "25 ft."
stats: [20, 8, 17, 9, 12, 10]
saves:
  - str: "+8"
  - con: "+6"
  - wis: "+4"
skillsaves:
  - athletics: "+8"
  - perception: "+4"
  - intimidation: "+3"
damage_immunities: "poison, fire"
damage_resistances: "necrotic; bludgeoning, piercing, slashing from nonmagical weapons"
condition_immunities: "charmed, exhaustion, frightened, poisoned"
senses: "darkvision 60 ft., passive Perception 14"
languages: "Abyssal, understands Common but does not speak"
cr: "8"
traits:
  - name: "Immovable Sentinel"
    desc: "Gorrath cannot be knocked Prone, pushed, or pulled by any means. He has advantage on all saves against forced movement."
  - name: "Spiked Bulwark"
    desc: "Any creature that hits Gorrath with a melee attack while he wields his tower shield takes 5 (1d10) piercing damage."
  - name: "Wall of One"
    desc: "While Gorrath has not moved on his last turn, he has +2 AC and cannot be flanked."
  - name: "No Face, No Fear"
    desc: "Immune to any effect requiring eye contact or reading the target's face. Spells requiring these automatically fail."
  - name: "Demonic Plate"
    desc: "When Gorrath takes 15+ damage from a single hit, he can reduce it by 10 as a reaction. 3 uses, refreshes on short/long rest."
actions:
  - name: "Multiattack"
    desc: "Gorrath makes two Broadsword attacks, or one Broadsword and one Shield Slam."
  - name: "Broadsword"
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 16 (2d10 + 5) slashing damage. On a crit, the target must succeed on a DC 16 Strength save or be knocked Prone."
  - name: "Shield Slam"
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12 (2d6 + 5) bludgeoning damage and the target must succeed on a DC 16 Strength save or be pushed 10 ft and have speed reduced to 0 until the start of its next turn."
  - name: "Warden's Roar (Recharge 5-6)"
    desc: "Gorrath slams his sword against his shield. Each creature within 30 ft must make a DC 15 Wisdom save or be Frightened for 1 minute. Fail by 5+: also Stunned until end of next turn."
bonus_actions:
  - name: "Defensive Stance"
    desc: "Gorrath raises his tower shield, gaining half cover (+2 AC, +2 Dex saves) until the start of his next turn. While in this stance, Shield Slam deals +7 (2d6) damage."
  - name: "Advance"
    desc: "Gorrath moves up to 10 ft toward a creature he can see without provoking opportunity attacks."
reactions:
  - name: "Interpose"
    desc: "When an ally within 5 ft is hit by an attack, Gorrath becomes the target instead. Requires his tower shield."
  - name: "Punish the Retreating"
    desc: "When a creature within 5 ft moves away from Gorrath, he makes one Broadsword attack against it as a reaction. He can use both Interpose and this in the same round."
```
