```
_True Name: Vael'shar_ (VAY-el-shar)
_Title: The Hollow_
_Classification: Demon General — Infiltration & Assassination_

In its true form Vael'shar stands roughly eight feet, its body a shifting compression of shadow that never quite resolves into solid edges. It is not dramatically monstrous. It is wrong in a quieter way — proportions that drift slightly, a face that suggests features without having them, the impression of a figure observed through dark water. It moves without sound. It does not telegraph. When it decides to end something, that thing ends.

```

```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Vael'shar — The Hollow"
size: "Large"
type: "fiend (demon)"
alignment: "neutral evil"
ac: 18
hp: 245
hit_dice: "28d10 + 84"
speed: "50 ft."
stats: [22, 24, 16, 18, 20, 16]
saves:
  - dex: "+13"
  - int: "+10"
  - wis: "+11"
skillsaves:
  - deception: "+15"
  - insight: "+11"
  - perception: "+11"
  - stealth: "+19"
damage_immunities: "poison, psychic"
damage_resistances: "cold, fire, lightning; bludgeoning, piercing, slashing from nonmagical attacks"
condition_immunities: "charmed, exhaustion, frightened, poisoned"
senses: "truesight 120 ft., darkvision 120 ft., passive Perception 21"
languages: "All languages (does not speak unless choosing to deceive)"
cr: "18"
traits:
  - name: "Shadow Form"
    desc: "Vael'shar can move through any space as narrow as one inch without squeezing. It does not trigger pressure plates, motion sensors, or tripwires."
  - name: "Flawless Mimicry"
    desc: "Vael'shar can perfectly replicate the appearance, voice, scent, and surface-level mannerisms of any creature observed for at least 1 minute. Detecting the disguise requires DC 28 Insight. Truesight bypasses it. Magical detection functions normally."
  - name: "Premeditated"
    desc: "Vael'shar always acts on the first round of combat, regardless of initiative. It cannot be surprised. Creatures attempting to ambush it must succeed on a DC 24 Deception check or Vael'shar is aware of the attempt."
  - name: "Hollow Presence"
    desc: "Creatures within 30 ft of Vael'shar in true form must make a DC 19 Wisdom save at the start of each turn or have disadvantage on attacks against it and lose reactions until the start of their next turn. Success: immune 24 hours."
  - name: "Shadow Anchor"
    desc: "Vael'shar's shadow exists independently of light sources — always present, always correct, even in magical darkness."
  - name: "Legendary Resistance (3/Day)"
    desc: "If Vael'shar fails a saving throw, it can choose to succeed instead."
actions:
  - name: "Multiattack"
    desc: "Vael'shar makes three Void Blade attacks. It can replace one with Hollow Touch."
  - name: "Void Blade"
    desc: "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 2d10+7 slashing + 3d8 necrotic damage. The target's HP maximum is reduced by the necrotic damage dealt until a long rest."
  - name: "Hollow Touch (Recharge 5-6)"
    desc: "Vael'shar reaches into a creature within 5 ft and touches something they fear losing. The target makes a DC 19 Wisdom save. On a failure: 6d10 psychic damage and stunned until end of next turn. On a success: half damage, not stunned."
  - name: "Unmaking Strike (1/Day)"
    desc: "Declared before the roll. On a hit: 4d12+7 piercing + 4d12 necrotic, and the target must make a DC 21 Constitution save or be reduced to 0 HP. On a miss: 2d12+7 damage as the blade grazes."
bonus_actions:
  - name: "Blink Step"
    desc: "Vael'shar teleports up to 60 ft to an unoccupied space it is aware of. Does not need line of sight. Does not provoke opportunity attacks."
  - name: "Read the Room"
    desc: "Vael'shar studies one creature within 60 ft. Until end of next turn: advantage on attacks and saves against it, and it has disadvantage on saves against Vael'shar's abilities."
reactions:
  - name: "Counterstrike"
    desc: "When a creature within 10 ft misses Vael'shar with a melee attack, it makes one Void Blade attack against them."
  - name: "Phase"
    desc: "When Vael'shar would take damage, it halves that damage and teleports up to 20 ft. Cannot Phase and Counterstrike in the same round."
  - name: "Legendary Actions"
    desc: "Vael'shar can take 3 legendary actions per round, at the end of another creature's turn. Shift (1): move half speed without provoking OAs. Shadow Lash (1): one creature within 30 ft, DC 19 Dex save or 2d8+7 necrotic + prone. Wear Their Face (2): assume the appearance of one creature seen within 60 ft — attacks against Vael'shar from those who can't identify it have disadvantage. Full Presence (3): drop all pretense — every creature within 30 ft that can see it must make a DC 21 Wis save or be frightened for 1 minute."
```
