```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Serpent Retainer"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful evil"
ac: 14
hp: 32
hit_dice: "5d8 + 10"
speed: "30 ft."
stats: [13, 16, 14, 10, 12, 10]
saves:
  - dex: "5"
skillsaves:
  - acrobatics: "5"
  - stealth: "5"
damage_resistances: "poison"
senses: "passive Perception 11"
languages: "Common, one regional dialect"
cr: "2"
traits:
  - name: "Cultivated Discipline"
    desc: "The retainer's weapon attacks count as magical. While not wearing armor, their AC equals 10 + their Dexterity modifier + their Wisdom modifier."
  - name: "Poisoned Blade"
    desc: "The retainer's blade is coated with venom. Any creature hit by their Serpent Fang attack must make a DC 13 Constitution saving throw or take 3 (1d6) poison damage and have its speed halved until the end of its next turn."
  - name: "Hidden Dagger"
    desc: "The retainer conceals a dagger in their sleeve. Once per turn, they can draw and throw it as a free action."
actions:
  - name: "Multiattack"
    desc: "The retainer makes one Serpent Fang attack and one Hidden Dagger throw."
  - name: "Serpent Fang"
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d8 + 3) slashing damage plus 3 (1d6) poison damage (see Poisoned Blade)."
  - name: "Hidden Dagger"
    desc: "Ranged Weapon Attack: +5 to hit, range 20/40 ft., one target. Hit: 5 (1d4 + 3) piercing damage."
bonus_actions:
  - name: "Sidestep"
    desc: "The retainer takes the Disengage action as a bonus action."
reactions:
  - name: "Defend the Clan Head"
    desc: "When Jin Hao or Mo Yan is targeted by an attack while within 5 ft. of the retainer, the retainer can use their reaction to impose disadvantage on the roll."
```
