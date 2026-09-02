```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Jin Hao"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful evil"
ac: 16
hp: 91
hit_dice: "14d8 + 28"
speed: "35 ft."
stats: [14, 18, 14, 14, 13, 17]
saves:
  - dex: "7"
  - cha: "6"
  - con: "5"
skillsaves:
  - acrobatics: "7"
  - deception: "6"
  - perception: "4"
  - stealth: "7"
damage_resistances: "poison"
senses: "passive Perception 14"
languages: "Common, one regional dialect"
cr: "6"
traits:
  - name: "Cultivated Discipline"
    desc: "Jin Hao's weapon attacks count as magical. While he is not wearing armor, his AC equals 10 + his Dexterity modifier + his Charisma modifier."
  - name: "Serpent Venom"
    desc: "Jin Hao's blade is coated with a paralytic poison. Any creature hit by his Venom Fang attack must make a DC 15 Constitution saving throw or have its speed halved and take disadvantage on Dexterity saving throws until the end of its next turn. He keeps a small vial of pure venom in his sleeve for emergencies."
  - name: "Hidden Arsenal"
    desc: "Jin Hao conceals weapons in his robes — sleeve needles, throwing darts, a concealed short blade. He has advantage on Sleight of Hand checks to draw or conceal them, and can draw a hidden weapon as a free action once per turn."
  - name: "Venomous Charm"
    desc: "Jin Hao has advantage on Charisma (Deception) and Charisma (Persuasion) checks against creatures he has not yet attacked. He is a predator wearing a smile."
  - name: "Poisoner's Resilience"
    desc: "Jin Hao has advantage on saving throws against being poisoned, and immunity to the poisoned condition."
actions:
  - name: "Multiattack"
    desc: "Jin Hao makes two Venom Fang attacks, or one Venom Fang and one Hidden Dart."
  - name: "Venom Fang"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 10 (1d8 + 4) slashing damage plus 7 (2d6) poison damage. The target must make a DC 15 Constitution saving throw or be poisoned until the end of its next turn (see Serpent Venom)."
  - name: "Hidden Dart"
    desc: "Ranged Weapon Attack: +7 to hit, range 30/60 ft., one target. Hit: 6 (1d4 + 4) piercing damage. The target must make a DC 15 Dexterity saving throw or the dart's poison takes hold — speed halved and disadvantage on Dexterity saves until the end of its next turn."
  - name: "Venom Mist (Recharge 5-6)"
    desc: "Jin Hao throws a sealed vial that bursts into a 15 ft. radius cloud of purple mist centered on a point within 30 ft. Each creature in the area must make a DC 15 Constitution saving throw or take 21 (6d6) poison damage and be poisoned for 1 minute. On a success, half damage and not poisoned. A poisoned creature repeats the save at the end of each of its turns."
bonus_actions:
  - name: "Flourish"
    desc: "Jin Hao makes a showy display of his blade, drawing attention. A creature of his choice within 30 ft. that can see him must make a DC 14 Wisdom saving throw or be distracted — it has disadvantage on its next attack roll against anyone other than Jin Hao."
  - name: "Sidestep"
    desc: "Jin Hao takes the Disengage action as a bonus action."
reactions:
  - name: "Catch the Blade"
    desc: "When a creature within 5 ft. misses Jin Hao with a melee attack, he can use his reaction to make one Venom Fang attack against that creature."
  - name: "Serpent's Grace"
    desc: "When Jin Hao would take damage, he can use his reaction to reduce the damage by 7 (2d6) — twisting away from the blow with practiced ease."
```
