```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Xiao Yun"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 15
hp: 78
hit_dice: "12d8 + 24"
speed: "35 ft."
stats: [12, 17, 14, 13, 15, 12]
saves:
  - dex: "5"
  - wis: "4"
skillsaves:
  - acrobatics: "5"
  - athletics: "3"
  - insight: "4"
  - perception: "4"
senses: "passive Perception 14"
languages: "Common, one regional dialect"
cr: "4"
traits:
  - name: "Cultivated Discipline"
    desc: "Xiao Yun's unarmed strikes and weapon attacks count as magical. While she is not wearing armor, her AC equals 10 + her Dexterity modifier + her Wisdom modifier."
  - name: "Trained Eye"
    desc: "Xiao Yun can use a bonus action to study a creature she can see. Until the end of her next turn, she has advantage on her first attack roll against that creature."
  - name: "Composure"
    desc: "Xiao Yun has advantage on saving throws against being frightened or charmed. She does not visibly react to intimidation — she simply takes note of whoever is trying."
  - name: "Disciple's Limit"
    desc: "Xiao Yun is competent, not exceptional. She has no spells, no legendary actions, and no abilities she hasn't been specifically taught. She knows this about herself. Most days, she's made peace with it."
actions:
  - name: "Multiattack"
    desc: "Xiao Yun makes two Flowing Strike attacks, or one Flowing Strike and one Precision Throw."
  - name: "Flowing Strike"
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (1d10 + 3) bludgeoning damage. If this attack hits, she can push the target 5 ft. in any direction (no save)."
  - name: "Precision Throw"
    desc: "Ranged Weapon Attack: +6 to hit, range 20/60 ft., one target. Hit: 7 (1d8 + 3) piercing damage. The target must succeed on a DC 14 Constitution saving throw or lose its reaction until the start of its next turn."
bonus_actions:
  - name: "Step Aside"
    desc: "Xiao Yun takes the Disengage action as a bonus action."
reactions:
  - name: "Intercept"
    desc: "When a creature within 5 ft. of Xiao Yun is targeted by an attack, she can use her reaction to impose disadvantage on the roll, stepping partially into the line of attack."
  - name: "Redirect (Recharge 5-6)"
    desc: "When a creature within 5 ft. misses Xiao Yun with a melee attack, she can use her reaction to redirect the blow — the attacker must make a DC 14 Dexterity saving throw or the attack hits a creature of Xiao Yun's choice within 5 ft. of the attacker instead."
```
