```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Serava, the Thorn Blade"
size: "Medium"
type: "fiend (demonoid)"
alignment: "chaotic evil"
ac: 18
hp: 97
hit_dice: "15d8 + 30"
speed: "40 ft."
stats: [17, 20, 14, 12, 14, 13]
saves:
  - dex: "+8"
  - str: "+6"
  - con: "+5"
skillsaves:
  - acrobatics: "+8"
  - athletics: "+6"
  - perception: "+5"
  - intimidation: "+4"
damage_immunities: "poison"
damage_resistances: "fire, necrotic; bludgeoning, piercing, slashing from nonmagical weapons"
condition_immunities: "charmed, frightened, poisoned"
senses: "darkvision 60 ft., passive Perception 15"
languages: "Abyssal, Common"
cr: "7"
traits:
  - name: "Thorn Arm"
    desc: "Any creature that grapples Serava or is grappled by her takes 5 (1d10) piercing damage at the start of each of its turns."
  - name: "Tail Sweep"
    desc: "Serava cannot be flanked. Any creature that moves through a space within 5 ft of her must make a DC 14 Dexterity save or take 7 (2d6) piercing damage and stop moving for that turn."
  - name: "Predator's Mask"
    desc: "Creatures automatically fail Insight checks to read Serava's intentions. She has advantage on Deception checks made through body language or silence."
  - name: "Fluid Aggression"
    desc: "When Serava reduces a creature to 0 HP, she can immediately move up to 15 ft without provoking opportunity attacks and make one additional Thorn Blade attack."
actions:
  - name: "Multiattack"
    desc: "Serava makes three Thorn Blade attacks. She can replace one with a Tail Lash."
  - name: "Thorn Blade"
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 12 (2d6 + 5) slashing damage. The target must succeed on a DC 15 Dexterity save or suffer one: Hooked (speed -10 ft), Opened (takes 5 (1d10) piercing at start of next turn), or Staggered (disadvantage on next attack)."
  - name: "Tail Lash"
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 10 (2d4 + 5) piercing damage and the target is knocked Prone on a failed DC 15 Strength save."
  - name: "Whirlwind Strike (Recharge 5-6)"
    desc: "Each creature within 10 ft must make a DC 16 Dexterity save, taking 28 (8d6) slashing damage on a failure or half on a success. Each failure is also Hooked (speed -15 ft until end of next turn)."
bonus_actions:
  - name: "Demon Dash"
    desc: "Serava moves up to 20 ft without provoking opportunity attacks. If she moves through a creature's space, that creature must make a DC 14 Dexterity save or take 7 (2d6) slashing damage."
  - name: "Thorn Grip"
    desc: "Serava attempts to grapple one creature within 5 ft (Athletics +6). A grappled creature is also Restrained and takes 5 (1d10) piercing at the start of each turn."
reactions:
  - name: "Deflect"
    desc: "When hit by a melee attack, Serava reduces the damage by 10 (2d4 + 5)."
  - name: "Riposte"
    desc: "When a creature within 5 ft misses Serava with a melee attack, she immediately makes one Thorn Blade attack against it."
```
