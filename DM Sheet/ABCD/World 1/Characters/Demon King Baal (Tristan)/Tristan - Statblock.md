```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Tristan — The Demon King, Baal"
size: "Medium"
type: "humanoid (demon)"
alignment: "neutral evil"
ac: 18
hp: 190
hit_dice: "20d8 + 80"
speed: "40 ft."
stats: [20, 16, 18, 16, 14, 12]
saves:
  str: 9
  con: 8
  int: 7
  wis: 6
skillsaves:
  athletics: 9
  perception: 6
  intimidation: 5
  arcana: 7
damage_immunities: "necrotic, poison"
damage_resistances: "fire, cold, bludgeoning, piercing, slashing from nonmagical attacks"
condition_immunities: "frightened, charmed, poisoned"
senses: "darkvision 120 ft., truesight 30 ft., passive Perception 16"
languages: "Common, Abyssal"
cr: "12"
traits:
  - name: "Demonic Physiology"
    desc: "Tristan has advantage on Strength checks and saving throws. He does not need to eat, drink, or sleep."
  - name: "Innate Mana"
    desc: "Tristan's magic cannot be suppressed by antimagic effects that target external mana sources."
  - name: "Dual Timeline Memory"
    desc: "Tristan retains memories of both timelines. He cannot be deceived by the players about past events and has advantage on Insight checks against them specifically."
  - name: "Oblivion Aura (Will — Stage III)"
    desc: "Tristan's Will radiates passively. Creatures within 15 ft. of Tristan have disadvantage on saving throws against his abilities. Creatures that fail a saving throw against him also have their damage reduced by 1d6 until the end of their next turn as Oblivion eats at their conviction."
  - name: "Partial Transformation"
    desc: "When Tristan uses any magic ability, his demonic traits emerge (horns, wings, red markings, glowing red eyes). His AC increases by 1 and he gains 15 temporary HP. If he uses two or more magic abilities in the same encounter, his AC increases by 2 total and he gains an additional 15 temporary HP."
  - name: "Legendary Resistance (2/Day)"
    desc: "If Tristan fails a saving throw, he can choose to succeed instead."
actions:
  - name: "Multiattack"
    desc: "Tristan makes three Demon Blade attacks. He can replace one with Corrupting Touch or Dark Pulse."
  - name: "Demon Blade"
    desc: "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 1d10+5 slashing plus 2d8 necrotic. On a hit the target makes a DC 16 Constitution save or has their maximum HP reduced by the necrotic damage dealt until they complete a long rest."
  - name: "Corrupting Touch"
    desc: "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 3d8 necrotic damage. The target must make a DC 16 Wisdom save or become Corrupted until the end of their next turn — while Corrupted, they have disadvantage on attacks against Tristan and must make a DC 14 Wisdom save at the start of each turn or use their movement to move toward him."
  - name: "Dark Pulse"
    desc: "Tristan releases a wave of compressed dark energy in a 20 ft. radius. Each creature makes a DC 16 Constitution save, taking 4d10 necrotic damage on a fail or half on a success. Triggers Partial Transformation."
  - name: "Will — Stage I: Darkness"
    desc: "Void Wall (action, 60 ft., concentration 1 min) — Raises a 30 ft. × 10 ft. wall of impenetrable darkness. Creatures inside are blinded and have speed halved. Cannot teleport through it. Tristan sees through it.\n\nConsuming Shadow (bonus action, 60 ft., 1 min) — Seeds darkness that expands 10 ft. per turn up to 30 ft. radius. Creatures inside are heavily obscured. Start of turn inside: DC 16 Con save or speed reduced by 10 ft."
  - name: "Will — Stage II: Dominion"
    desc: "Dominating Pulse (action, self 30 ft. radius) — Each creature makes a DC 16 Wisdom save. Fail: 3d8 necrotic damage and Dominated — must move toward Tristan on their next turn, no reactions. Success: half damage.\n\nSubjugate (action, 15 ft., concentration 1 min) — One creature makes a DC 16 Wisdom save or falls under Dominion — cannot willingly move away from Tristan, disadvantage on attacks against him. Repeats save at end of each turn."
  - name: "Will — Stage III: Oblivion"
    desc: "Oblivion Field (action, self 30 ft. radius, concentration 1 min) — All creatures in range have resistances, immunities, and damage reduction suppressed. Cannot benefit from temporary HP. Make all saves against Tristan with disadvantage. Spells cannot be cast. Tristan cannot move while this is active.\n\nUnmaking Strike (action, 5 ft.) — Requires Oblivion Field active. On hit: weapon damage + 4d12 necrotic. Target makes a DC 18 Wisdom save or is reduced to 0 HP if at or below half maximum. Against gods or divine beings, save made with disadvantage."
bonus_actions:
  - name: "Blink Step"
    desc: "Tristan teleports up to 40 ft. to an unoccupied space he can see."
  - name: "Corrupt the Wound"
    desc: "One creature within 30 ft. that is below half HP must make a DC 16 Wisdom save or become Corrupted until the end of their next turn."
reactions:
  - name: "Instinctive Block"
    desc: "When hit by an attack, Tristan reduces the damage by 1d10+5."
  - name: "Oblivion Counter"
    desc: "When a creature within 5 ft. misses Tristan with a melee attack, he can make one Demon Blade attack against them as a reaction."
legendary_actions:
  - name: "Shift (1 action)"
    desc: "Tristan moves up to half his speed without provoking opportunity attacks."
  - name: "Shadow Lash (1 action)"
    desc: "One creature within 30 ft. makes a DC 16 Dexterity save or takes 2d10 necrotic damage and is knocked prone."
  - name: "Corrupt (2 actions)"
    desc: "One creature within 60 ft. makes a DC 16 Wisdom save or becomes Corrupted for 1 minute. They can repeat the save at the end of each of their turns."
```
