```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Mo Yan"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful evil"
ac: 15
hp: 58
hit_dice: "9d8 + 18"
speed: "35 ft."
stats: [12, 18, 14, 13, 14, 12]
saves:
  - dex: "7"
  - wis: "5"
skillsaves:
  - acrobatics: "7"
  - stealth: "7"
  - perception: "5"
damage_resistances: "poison"
senses: "passive Perception 15"
languages: "Common, one regional dialect"
cr: "4"
traits:
  - name: "Cultivated Discipline"
    desc: "Mo Yan's weapon attacks count as magical. While she is not wearing armor, her AC equals 10 + her Dexterity modifier + her Wisdom modifier."
  - name: "Ink Swallow"
    desc: "Mo Yan fights silently and efficiently. She has advantage on initiative rolls and deals an extra 7 (2d6) damage against creatures that have not yet acted in combat."
  - name: "Hidden Arsenal"
    desc: "Mo Yan conceals her weapons — needles, darts, and a weighted chain. She can draw a hidden weapon as a free action once per turn and has advantage on Sleight of Hand checks to conceal them."
  - name: "The Clan Head's Shadow"
    desc: "Mo Yan acts as Jin Hao's escort and enforcer. While within 10 ft. of Jin Hao, she has advantage on saving throws against being frightened or charmed, and she will take a blow meant for him without hesitation."
actions:
  - name: "Multiattack"
    desc: "Mo Yan makes two Hidden Needle attacks, or one Hidden Needle and one Chain Strike."
  - name: "Hidden Needle"
    desc: "Ranged Weapon Attack: +7 to hit, range 30/60 ft., one target. Hit: 5 (1d4 + 4) piercing damage. The target must make a DC 14 Constitution saving throw or take 7 (2d6) poison damage and have its speed halved until the end of its next turn."
  - name: "Chain Strike"
    desc: "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 7 (1d6 + 4) bludgeoning damage. The target must make a DC 14 Strength saving throw or be pulled 5 ft. toward Mo Yan."
  - name: "Needle Storm (Recharge 5-6)"
    desc: "Mo Yan flings a fan of needles in a 15 ft. cone. Each creature in the area must make a DC 14 Dexterity saving throw, taking 14 (4d6) piercing damage on a failure or half on a success. Each creature that fails is also poisoned for 1 minute (repeat save at end of each turn)."
bonus_actions:
  - name: "Sidestep"
    desc: "Mo Yan takes the Disengage action as a bonus action."
reactions:
  - name: "Shield the Serpent"
    desc: "When Jin Hao is targeted by an attack while within 10 ft. of Mo Yan, she can use her reaction to impose disadvantage on the roll — stepping between the blow and her clan head."
```
