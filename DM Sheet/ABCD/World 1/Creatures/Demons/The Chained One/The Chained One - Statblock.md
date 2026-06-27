```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "The Chained One"
size: "Large"
type: "fiend (demon-touched humanoid)"
alignment: "chaotic evil"
ac: 16
hp: 136
hit_dice: "16d10 + 48"
speed: "25 ft."
stats: [22, 8, 17, 7, 10, 6]
saves:
  - str: "+9"
  - con: "+6"
skillsaves:
  - athletics: "+9"
  - intimidation: "+4"
damage_immunities: "poison; bludgeoning from nonmagical weapons"
damage_resistances: "fire, necrotic; piercing, slashing from nonmagical weapons"
condition_immunities: "charmed, exhaustion, frightened, poisoned"
senses: "darkvision 60 ft., passive Perception 10"
languages: "Understands Abyssal and Common, does not speak"
cr: "7"
traits:
  - name: "Skull-Bound"
    desc: "The Chained One has advantage on saves against being banished. For every creature it has killed in the current encounter, it gains a cumulative +1 bonus to damage rolls (max +5)."
  - name: "Inexorable"
    desc: "Cannot be knocked Prone, pushed, or pulled by any effect of CR 8 or lower. Teleportation and forced movement automatically fail against it."
  - name: "Demonic Resilience"
    desc: "If The Chained One starts its turn with 68 HP or fewer, it regains 10 HP at the start of each of its turns. Does not function if it has taken radiant damage since its last turn."
  - name: "Crushing Presence"
    desc: "Any creature that starts its turn within 10 ft must succeed on a DC 15 Strength save or have its speed reduced to 0 until the start of its next turn."
actions:
  - name: "Multiattack"
    desc: "The Chained One makes one Spiked Maul attack and one Chain Lash attack."
  - name: "Spiked Maul"
    desc: "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 22 (3d10 + 6) bludgeoning + piercing damage. If this reduces a creature to 0 HP, all creatures within 15 ft must make a DC 16 Wisdom save or be Frightened until end of next turn."
  - name: "Chain Lash"
    desc: "Melee Weapon Attack: +9 to hit, reach 15 ft., one target. Hit: 14 (2d6 + 6) slashing damage and the target is Grappled (escape DC 17). While grappled, the target is Restrained. Can grapple up to two creatures."
  - name: "Drag Down (Recharge 5-6)"
    desc: "Each creature currently Grappled by The Chained One is slammed into the ground. Each must make a DC 17 Strength save, taking 28 (8d6) bludgeoning damage and falling Prone on a failure, or half damage on a success. The grapple then ends."
bonus_actions:
  - name: "Rattle the Chains"
    desc: "Each creature within 30 ft that can hear it must succeed on a DC 13 Wisdom save or be Frightened until end of next turn."
reactions:
  - name: "Dead Weight"
    desc: "When a creature within 15 ft attempts to move away from The Chained One, it makes one Chain Lash attack against that creature. On a hit, the creature's movement is reduced to 0 for that turn."
```
