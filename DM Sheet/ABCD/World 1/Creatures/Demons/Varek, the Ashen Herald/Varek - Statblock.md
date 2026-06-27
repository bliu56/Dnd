```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Varek, the Ashen Herald"
size: "Medium"
type: "undead (death herald)"
alignment: "lawful evil"
ac: 17
hp: 112
hit_dice: "15d8 + 45"
speed: "30 ft., hover 10 ft."
stats: [18, 12, 16, 14, 16, 18]
saves:
  - str: "+7"
  - wis: "+6"
  - cha: "+7"
skillsaves:
  - arcana: "+5"
  - perception: "+6"
  - intimidation: "+7"
  - religion: "+5"
damage_immunities: "poison, necrotic"
damage_resistances: "fire, cold; bludgeoning, piercing, slashing from nonmagical weapons"
condition_immunities: "charmed, exhaustion, frightened, paralyzed, poisoned"
senses: "darkvision 120 ft., truesight 30 ft., passive Perception 16"
languages: "Common, Abyssal, the language of the dead"
cr: "8"
traits:
  - name: "Soul Sense"
    desc: "Varek knows the exact location of every living creature within 60 ft, even through walls and magical darkness. She cannot be surprised."
  - name: "Crown of Thorns"
    desc: "Whenever Varek casts a soul spell or uses a soul ability, creatures within 10 ft must succeed on a DC 15 Wisdom save or be Frightened until end of next turn."
  - name: "Death's Threshold"
    desc: "When a creature dies within 60 ft of Varek, she regains 10 HP and gains +1 to attack rolls until end of her next turn. Once per turn."
  - name: "Undying Herald"
    desc: "The first time Varek drops to 0 HP, she drops to 1 HP instead and becomes incorporeal until the start of her next turn — damage halved, cannot be grappled or restrained. Then returns to physical form."
actions:
  - name: "Multiattack"
    desc: "Varek makes two Soul Cleaver attacks, or one Soul Cleaver and uses one soul ability."
  - name: "Soul Cleaver"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 17 (2d12 + 4) slashing plus 9 (2d8) necrotic damage. The target must make a DC 15 Constitution save or have its HP maximum reduced by the necrotic damage dealt until a long rest. Reduced to 0 HP this way: dies and cannot be resurrected by 5th level spells or lower."
  - name: "Soul Rend"
    desc: "Ranged Spell Attack: +7 to hit, range 60 ft., one target. Hit: 18 (4d8) necrotic damage. The target must succeed on a DC 15 Wisdom save or be Stunned until end of next turn. On success: Incapacitated until end of next turn."
  - name: "Reaping Wave (Recharge 5-6)"
    desc: "Each creature in a 15 ft cone must make a DC 16 Dexterity save, taking 21 (6d6) slashing and 14 (4d6) necrotic damage on a failure or half on a success. Failures also have speed halved until end of next turn."
  - name: "Soul Grasp"
    desc: "Varek reaches toward one creature within 30 ft. The target must make a DC 15 Charisma save. On a failure: the target cannot use reactions and must use its next action to move toward Varek. On a success: 14 (4d6) psychic damage."
bonus_actions:
  - name: "Herald's Step"
    desc: "Varek vanishes and reappears within 30 ft. Any creature within 5 ft of her departure point takes 7 (2d6) necrotic damage (DC 14 Wis save negates)."
  - name: "Mark for Reaping"
    desc: "Varek marks one creature within 60 ft. Until the end of the encounter or the creature dies, Varek's attacks deal +7 (2d6) necrotic damage to it and it cannot regain HP from any source below 3rd level."
reactions:
  - name: "Soul Anchor"
    desc: "When a creature within 30 ft attempts to teleport or use planar travel, Varek forces a DC 15 Charisma save. On failure: the movement fails and the creature takes 14 (4d6) necrotic damage."
  - name: "Spectral Deflection"
    desc: "When hit by an attack, Varek reduces the damage by 14 (4d6). If reduced to 0, the attack passes through her entirely."
```
