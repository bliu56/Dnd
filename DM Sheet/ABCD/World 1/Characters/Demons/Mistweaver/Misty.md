```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "The Mistweaver"
size: "Medium"
type: "monstrosity"
alignment: "unaligned"
ac: 16
hp: 152
hit_dice: "16d10 + 64"
speed: "30 ft., fly 50 ft. (hover)"
stats: [12, 20, 18, 16, 16, 14]
saves:
  - dex: "+9"
  - con: "+8"
  - wis: "+7"
skillsaves:
  - perception: "+11"
  - stealth: "+13"
  - acrobatics: "+9"
damage_resistances: "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
condition_immunities: "blinded, charmed, frightened"
senses: "blindsight 60 ft. (blind beyond this radius in fog), tremorsense 30 ft., darkvision 120 ft., passive Perception 21"
languages: "Understands Sylvan but does not speak"
cr: "9"
traits:
  - name: "Spore Cloud"
    desc: "At the start of each of the Mistweaver's turns, a 30 ft radius cloud of magical spores erupts from its body, heavily obscuring the area for 1 minute. Any creature that starts its turn in the cloud or enters it for the first time on a turn must make a DC 16 Constitution save or become disoriented for 1 minute. While disoriented: the creature cannot take reactions, and at the start of each of its turns it must roll a d8 to determine a random direction — it moves 10 ft in that direction before taking any other action. A creature can repeat the save at the end of each of its turns."
  - name: "Spore Sensitivity"
    desc: "The Mistweaver is immune to its own Spore Cloud and sees through it perfectly. It knows the exact location of every creature inside the cloud at all times."
  - name: "Canopy Camouflage"
    desc: "While in forested terrain and remaining motionless, the Mistweaver is effectively invisible from the ground. It has advantage on Stealth checks made to hide in trees or foliage."
  - name: "Magic Resistance"
    desc: "The Mistweaver has advantage on saving throws against spells and other magical effects."
actions:
  - name: "Multiattack"
    desc: "The Mistweaver makes two Wing Slash attacks."
  - name: "Wing Slash"
    desc: "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 13 (2d8 + 5) slashing damage. The target must succeed on a DC 16 Constitution save or be blinded until the end of its next turn."
  - name: "Focused Burst (Recharge 5-6)"
    desc: "The Mistweaver beats its wings in a focused 30 ft cone. Each creature in the area must make a DC 16 Strength save or take 21 (6d6) thunder damage, be knocked prone, and become disoriented for 1 minute (see Spore Cloud). On a success: half damage, not prone or disoriented."
  - name: "Scatter"
    desc: "The Mistweaver targets one disoriented creature it can see within 60 ft. The target must make a DC 16 Wisdom save. On a failure: the target uses its reaction to move its full speed in a random direction. If this movement would cause it to enter a hazard (pit, fire, edge, etc.), it makes a DC 14 Dexterity save to stop just before the hazard instead."
bonus_actions:
  - name: "Lift"
    desc: "The Mistweaver targets one blinded or prone creature within 30 ft. The target is lifted 20 ft into the air (no save). At the start of the Mistweaver's next turn, the target falls, taking 2d6 bludgeoning damage and landing prone."
reactions:
  - name: "Ascend"
    desc: "When the Mistweaver takes 20 or more damage from a single source, it can use its reaction to fly straight up to 30 ft into the canopy. Until the start of its next turn, ranged attacks against it have disadvantage."
```
