```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Veyrath, the Ashen Blade"
size: "Medium"
type: "fiend (demonoid)"
alignment: "neutral evil"
ac: 17
hp: 110
hit_dice: "17d8 + 34"
speed: "40 ft."
stats: [16, 18, 14, 16, 12, 17]
saves:
  - dex: "+7"
  - int: "+6"
  - cha: "+6"
skillsaves:
  - arcana: "+6"
  - athletics: "+6"
  - perception: "+4"
  - intimidation: "+6"
damage_immunities: "poison"
damage_resistances: "fire, necrotic; bludgeoning, piercing, slashing from nonmagical weapons"
condition_immunities: "charmed, poisoned, frightened"
senses: "darkvision 60 ft., passive Perception 14"
languages: "Common, Abyssal, Infernal"
cr: "8"
traits:
  - name: "Void Aura"
    desc: "Any creature that starts its turn within 5 ft of Veyrath takes 5 (1d10) necrotic damage."
  - name: "Arcane Poise"
    desc: "Veyrath does not provoke opportunity attacks when casting spells. He can move up to 15 ft as a free action after casting a spell (once per turn)."
  - name: "The Orb Watches"
    desc: "Once per round, when Veyrath is hit by an attack, he halves the damage as a reaction (the orb absorbs it). The orb is destroyed if it absorbs 30+ damage in a single hit. Can be resummoned as a bonus action."
  - name: "Demonic Focus"
    desc: "Veyrath has advantage on Concentration saves and cannot be disarmed of his sword."
actions:
  - name: "Multiattack"
    desc: "Veyrath makes two Ashen Blade attacks, or one Ashen Blade and casts one spell of 2nd level or lower without expending a slot."
  - name: "Ashen Blade"
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) slashing plus 7 (2d6) force damage. The target must succeed on a DC 14 Constitution save or have disadvantage on its next attack roll."
  - name: "Arcane Blast"
    desc: "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 18 (4d8) force damage. If the target is within 10 ft of another creature, the second creature must make a DC 14 Dexterity save or take 9 (2d8) force damage."
  - name: "Void Eruption (Recharge 5-6)"
    desc: "Each creature in a 20 ft radius must make a DC 15 Dexterity save, taking 35 (10d6) force damage on a failure or half on a success. The area becomes difficult terrain with purple smoke until the end of Veyrath's next turn."
  - name: "Spellcasting"
    desc: "Veyrath is an 8th-level spellcaster (Charisma, spell save DC 14, +6 to hit). Cantrips: Eldritch Blast, Prestidigitation. 1st (4 slots): Hex, Shield. 2nd (3 slots): Misty Step, Darkness. 3rd (2 slots): Counterspell, Hunger of Hadar. 4th (1 slot): Banishment."
bonus_actions:
  - name: "Blink Step"
    desc: "Veyrath teleports up to 30 ft, leaving a trail of violet smoke. Any creature in the arrival space takes 7 (2d6) force damage (DC 13 Dex save negates)."
  - name: "Resummon the Orb"
    desc: "Veyrath recalls and restores his arcane orb, resetting The Orb Watches trait."
reactions:
  - name: "Arcane Riposte"
    desc: "When a creature misses Veyrath with a melee attack, he makes one Ashen Blade attack against it."
  - name: "Counterspell"
    desc: "When a creature within 60 ft casts a spell, Veyrath can attempt to counter it (3rd level slot)."
```
