```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Caelen, the Bleeding Hand"
size: "Medium"
type: "fiend (demon-touched humanoid)"
alignment: "neutral evil"
ac: 15
hp: 104
hit_dice: "16d8 + 32"
speed: "35 ft."
stats: [10, 16, 14, 18, 13, 16]
saves:
  - dex: "+6"
  - int: "+7"
  - con: "+5"
skillsaves:
  - arcana: "+7"
  - perception: "+4"
  - deception: "+6"
  - medicine: "+4"
damage_immunities: "poison"
damage_resistances: "necrotic, fire"
condition_immunities: "frightened, poisoned"
senses: "darkvision 60 ft., passive Perception 14"
languages: "Common, Abyssal, Infernal"
cr: "7"
traits:
  - name: "Blood Sense"
    desc: "Caelen can smell blood within 60 ft. He always knows the current HP total of any creature that has taken damage this encounter. He has advantage on attack rolls against any creature below half its HP maximum."
  - name: "Hemorrhagic Aura"
    desc: "Any creature that starts its turn within 10 ft of Caelen while Bleeding takes an additional 3 (1d6) necrotic damage."
  - name: "Demonic Resilience"
    desc: "When Caelen drops to 0 HP for the first time in an encounter, he instead drops to 1 HP. All creatures within 15 ft must make a DC 14 Wisdom save or be Frightened until the end of their next turn. Cannot be used again until a long rest."
  - name: "Sigil Cloak"
    desc: "Caelen has advantage on saving throws against spells that force movement or restrain him."
  - name: "Bleeding Condition"
    desc: "A Bleeding creature takes 5 (1d10) necrotic damage at the start of each of its turns. Can end by using an action to make a DC 13 Medicine check, or by receiving any magical healing."
actions:
  - name: "Multiattack"
    desc: "Caelen makes two Blood Lance attacks, or one Blood Lance and casts one blood spell."
  - name: "Blood Lance"
    desc: "Ranged Spell Attack: +7 to hit, range 60 ft., one target. Hit: 14 (3d6 + 4) necrotic damage and the target must succeed on a DC 15 Constitution save or begin Bleeding."
  - name: "Crimson Burst"
    desc: "Area Attack: Caelen detonates the blood inside a Bleeding creature within 60 ft. The target takes 21 (6d6) necrotic damage (no save) and the Bleeding condition ends. Each creature within 10 ft of the target must make a DC 15 Dexterity save or take 10 (3d6) necrotic damage."
  - name: "Sanguine Chains (Recharge 5-6)"
    desc: "Blood erupts from the ground in a 20 ft radius centered on a point within 60 ft. Each creature in the area must make a DC 15 Strength save or be Restrained. A Restrained creature can repeat the save at the end of each turn. Bleeding creatures have disadvantage on this save."
  - name: "Drain"
    desc: "Melee Spell Attack: +7 to hit, reach 5 ft., one target. Hit: 18 (4d8) necrotic damage and Caelen regains HP equal to half the damage dealt. The target begins Bleeding if it isn't already."
bonus_actions:
  - name: "Open the Wound"
    desc: "Caelen chooses one Bleeding creature within 60 ft. That creature's Bleeding damage increases from 1d10 to 2d10 until the condition is removed. Once per creature per encounter."
  - name: "Crimson Step"
    desc: "Caelen teleports up to 20 ft to an unoccupied space, leaving a blood splatter behind. Any creature moving through that space before Caelen's next turn must make a DC 13 Dexterity save or begin Bleeding."
reactions:
  - name: "Blood Shield"
    desc: "When Caelen is hit by an attack, he can spend the blood of a Bleeding creature within 30 ft — that creature takes 9 (2d8) necrotic damage and Caelen reduces the incoming damage by the same amount."
  - name: "Redirect"
    desc: "When targeted by a spell of 3rd level or lower, Caelen can make a DC 13 + spell level Arcana check. On a success, he redirects the spell to a Bleeding creature within 60 ft."
```
