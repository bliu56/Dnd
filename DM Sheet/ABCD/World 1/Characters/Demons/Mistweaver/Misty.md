```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Misty — The Mistweaver Ascended"
size: "Medium"
type: "monstrosity"
alignment: "neutral evil"
ac: 17
hp: 195
hit_dice: "26d10 + 52"
speed: "40 ft., fly 60 ft. (hover)"
stats: [14, 22, 18, 18, 18, 16]
saves:
  - dex: "+10"
  - con: "+8"
  - wis: "+8"
skillsaves:
  - perception: "+12"
  - stealth: "+14"
  - acrobatics: "+10"
  - deception: "+11"
damage_resistances: "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
damage_immunities: "poison"
condition_immunities: "blinded, charmed, frightened, poisoned"
senses: "blindsight 60 ft. (blind beyond this radius in fog), darkvision 120 ft., passive Perception 22"
languages: "Understands Sylvan and Common but does not speak"
cr: "11"
traits:
  - name: "Spore Cloud"
    desc: "At the start of each of the Mistweaver's turns, a 30 ft radius cloud of magical spores erupts from its body, heavily obscuring the area for 1 minute. Any creature that starts its turn in the cloud or enters it for the first time on a turn takes 7 (2d6) psychic damage and must make a DC 17 Constitution save or become disoriented for 1 minute. While disoriented: the creature cannot take reactions, and at the start of each of its turns it must roll a d8 to determine a random direction — it moves 10 ft in that direction before taking any other action. A creature can repeat the save at the end of each of its turns."
  - name: "Spore Sensitivity"
    desc: "The Mistweaver is immune to its own Spore Cloud and sees through it perfectly. It knows the exact location of every creature inside the cloud at all times."
  - name: "Canopy Camouflage"
    desc: "While in forested terrain and remaining motionless, the Mistweaver is effectively invisible from the ground. It has advantage on Stealth checks made to hide in trees or foliage."
  - name: "Magic Resistance"
    desc: "The Mistweaver has advantage on saving throws against spells and other magical effects."
actions:
  - name: "Multiattack"
    desc: "The Mistweaver makes three Wing Slash attacks."
  - name: "Wing Slash"
    desc: "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 15 (3d6 + 6) slashing damage. The target must succeed on a DC 17 Constitution save or be blinded until the end of its next turn."
  - name: "Focused Burst (Recharge 5-6)"
    desc: "The Mistweaver beats its wings in a focused 30 ft cone. Each creature in the area must make a DC 17 Strength save. On a failure: 24 (7d6) thunder damage, knocked prone, and becomes disoriented for 1 minute. On a success: half damage, not prone or disoriented."
  - name: "Scatter"
    desc: "The Mistweaver targets one disoriented creature within 60 ft. The target must make a DC 17 Wisdom save. On a failure: the target perceives an ally as a threat and must use its reaction to move its full speed toward that ally and make one melee attack against them. On a success: the target takes 10 (3d6) psychic damage as the illusion shatters."
  - name: "Friendly Fire (Recharge 5-6)"
    desc: "The Mistweaver weaves an illusion over one creature within 60 ft, making them appear as a horrific enemy to their allies. Until the start of the Mistweaver's next turn, the first time an ally of the target targets them with a spell or attack, that ally must make a DC 17 Wisdom save. On a failure, the ally uses their action to attack the illusion-perceived target instead, believing they are striking a real enemy."
bonus_actions:
  - name: "Whispers in the Mist"
    desc: "The Mistweaver whispers to one disoriented creature within 60 ft. The target must make a DC 17 Wisdom save. On a failure: the target's next action must be used to attack the nearest creature (ally or enemy) — it cannot distinguish friend from foe."
  - name: "Lift"
    desc: "The Mistweaver targets one blinded or prone creature within 30 ft. The target is lifted 20 ft into the air (no save). At the start of the Mistweaver's next turn, the target falls, taking 2d6 bludgeoning damage and landing prone."
reactions:
  - name: "Ascend"
    desc: "When the Mistweaver takes 20 or more damage from a single source, it uses its reaction to fly straight up to 30 ft. Until the start of its next turn, ranged attacks against it have disadvantage."
```
