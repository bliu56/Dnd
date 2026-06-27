```statblock
columns: 1
columnWidth: 700px

layout: Basic 5e Layout
name: "Ash"
size: "Medium"
type: "humanoid (demon)"
alignment: "neutral evil"
ac: 16
hp: 130
hit_dice: "17d8 + 51"
speed: "50 ft., climb 40 ft."
stats: [19, 22, 16, 14, 16, 10]
saves:
  - dex: "+9"
  - wis: "+6"
skillsaves:
  - perception: "+6"
  - stealth: "+12"
  - survival: "+6"
  - insight: "+6"
damage_resistances: "fire, necrotic"
senses: "darkvision 120 ft., passive Perception 16"
languages: "Common, Abyssal"
cr: "7"
traits:
  - name: "Blind Side"
    desc: "Ash has a blind spot on his left. Attacks from directly to his left have advantage. He has disadvantage on Perception checks involving his left side."
  - name: "Trap Sense"
    desc: "Ash has advantage on saves and ability checks to detect or avoid traps. He will not approach a location that feels deliberately prepared."
  - name: "Pounce"
    desc: "If Ash moves at least 20 ft toward a target and hits with a Blade Strike, the target must make a DC 15 Strength save or be knocked prone. If prone, Ash makes a second Blade Strike as a bonus action."
  - name: "Patient Hunter"
    desc: "If Ash does not attack on his turn, he has advantage on his first attack roll on his next turn."
  - name: "Corrupted Instinct"
    desc: "Ash cannot be surprised while conscious and has advantage on initiative rolls."
  - name: "Will — Stage I: Speed (3/Short Rest)"
    desc: "Blur: As a bonus action, Ash's speed doubles, he moves through creatures without provoking opportunity attacks, and his first Blade Strike this turn deals +2d6 damage. Afterimage: While Blur is active, creatures attacking Ash must make a DC 15 Wisdom save or attack the afterimage instead (auto-miss). Creatures that succeed see through it."
  - name: "Will — Stage II: Precision"
    desc: "Precision Strike: Once per turn when Ash hits with a Blade Strike while at advantage, the attack deals +3d6 damage and the target cannot use reactions until the start of their next turn. Calculated Aggression (1/Long Rest): Ash activates Blur and immediately makes a full Multiattack at advantage. Every hit triggers Precision Strike. After the attacks, the target must make a DC 16 Constitution save or be stunned until end of their next turn."
actions:
  - name: "Multiattack"
    desc: "Ash makes two Blade Strike attacks."
  - name: "Blade Strike"
    desc: "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 3d8+6 slashing damage."
  - name: "Calculated Burst (Recharge 5-6)"
    desc: "Ash makes three Blade Strike attacks against one target. Each hit after the first deals an additional 1d6 damage."
  - name: "Vanish"
    desc: "Ash takes the Hide action and moves up to half his speed without provoking opportunity attacks. He cannot be tracked by scent or sound until the start of his next turn."
bonus_actions:
  - name: "Read the Opening"
    desc: "Ash studies one creature within 60 ft. Until the end of his next turn, he has advantage on all attack rolls against that creature and ignores half and three-quarters cover."
reactions:
  - name: "Sidestep"
    desc: "When Ash is targeted by a ranged attack, he moves up to 10 ft in any direction. If this moves him out of the attack's path, the attack misses automatically."
  - name: "Precision Counter"
    desc: "When a creature misses Ash with a melee attack, he makes one Blade Strike against them. If at advantage, it triggers Precision Strike."
```
