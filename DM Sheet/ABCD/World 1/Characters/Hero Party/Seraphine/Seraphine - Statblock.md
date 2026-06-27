```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Seraphine Vane — The Equation"
size: "Medium"
type: "humanoid (human)"
alignment: "lawful neutral"
ac: 13
hp: 91
hit_dice: "14d8 + 28"
speed: "30 ft."
stats: [8, 14, 14, 20, 14, 12]
saves:
  - int: "+8"
  - wis: "+5"
skillsaves:
  - arcana: "+11"
  - history: "+8"
  - investigation: "+8"
  - perception: "+5"
senses: "passive Perception 15"
languages: "Common, two noble dialects, Draconic"
cr: "7"
traits:
  - name: "Vane Bloodline"
    desc: "Seraphine's spells ignore resistance to their damage type. Her magical lineage is old enough that most defenses were not built with it in mind."
  - name: "Chain Calculus"
    desc: "When Seraphine deals damage to a creature with a spell, she marks it with a Calculus Sigil that lasts until the end of her next turn (one sigil active at a time). When she damages a marked creature with another spell before the sigil expires, it detonates in a 10 ft radius centered on the target. Each creature in the area must make a DC 16 Dexterity save or take 2d8 force damage, or half on a success."
  - name: "Arcane Ward"
    desc: "Seraphine has a magical ward with 20 HP. When she takes damage, the ward absorbs it first. The ward recharges 10 HP at the start of each of her turns if it has not been reduced to 0."
  - name: "Spellcasting"
    desc: "Seraphine is a 10th level spellcaster (Intelligence, spell save DC 16, +8 to hit). Cantrips: Fire Bolt, Ray of Frost, Mage Hand. 1st (4 slots): Burning Hands, Thunderwave. 2nd (3 slots): Shatter, Aganazzar's Scorcher. 3rd (3 slots): Fireball, Lightning Bolt, Sleet Storm. 4th (3 slots): Ice Storm, Vitriolic Sphere, Wall of Fire. 5th (2 slots): Cone of Cold, Cloudkill."
actions:
  - name: "Multiattack"
    desc: "Seraphine casts two cantrips or one cantrip and one leveled spell."
  - name: "Fire Bolt"
    desc: "Ranged Spell Attack: +8 to hit, range 120 ft., one target. Hit: 2d10 fire damage."
  - name: "Ray of Frost"
    desc: "Ranged Spell Attack: +8 to hit, range 60 ft., one target. Hit: 2d8 cold damage. The target's speed is reduced by 10 ft until the start of Seraphine's next turn."
bonus_actions:
  - name: "Calculated Repositioning"
    desc: "Seraphine moves up to 15 ft without provoking opportunity attacks."
  - name: "Misty Step"
    desc: "Briefly surrounded by silvery mist, Seraphine teleports up to 30 ft to an unoccupied space she can see."
reactions:
  - name: "Arcane Deflection"
    desc: "When Seraphine is hit by an attack, she adds +4 to her AC against that attack. If it still hits, the ward absorbs damage first."
  - name: "Counterspell"
    desc: "When a creature within 60 ft casts a spell, Seraphine can attempt to counter it. Spells of 3rd level or lower are automatically countered. Spells of 4th level or higher require an Intelligence check (DC 10 + spell level)."
```
