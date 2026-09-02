```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Falling Leaf Student"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 13
hp: 27
hit_dice: "5d8 + 5"
speed: "30 ft."
stats: [12, 14, 12, 10, 12, 11]
saves:
  - dex: "4"
skillsaves:
  - acrobatics: "4"
  - athletics: "3"
  - perception: "3"
senses: "passive Perception 13"
languages: "Common, one regional dialect"
cr: "1"
traits:
  - name: "Cultivated Discipline"
    desc: "The student's weapon attacks count as magical. While not wearing armor, their AC equals 10 + their Dexterity modifier + their Wisdom modifier."
  - name: "Sect Formation"
    desc: "While within 5 ft. of another Falling Leaf student, the student has advantage on saving throws against being frightened or charmed. They fight as one — that is the sect's way."
  - name: "Disciple's Limit"
    desc: "The student knows only the First Form of the Falling Leaf Sword Art. They are eager to prove themselves and terrified of failing their seniors."
actions:
  - name: "Multiattack"
    desc: "The student makes one Falling Leaf attack."
  - name: "Falling Leaf — First Form"
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d8 + 2) slashing damage. If two or more students target the same creature this turn, each gains a +1 bonus to hit against it (max +2)."
bonus_actions:
  - name: "Nervous Step"
    desc: "The student takes the Disengage action as a bonus action, then moves up to 5 ft. They are not brave — they are trained."
reactions:
  - name: "Protect the Senior"
    desc: "When a creature within 5 ft. of the student targets Xiao Yun or Xiao Feng with an attack, the student can use their reaction to impose disadvantage on the roll — stepping in the way even though they are afraid."
```
