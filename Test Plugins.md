[init tracker](obsidian://show-plugin?id=initiative-tracker)
[statblocks](obsidian://show-plugin?id=obsidian-5e-statblocks)

# TITOLO

[[Test Plugins#]]

```encounter
name: Example encounter
party: lol
creatures:
 - 3: Goblin
```

```statblock
image: [[Wikilink To Image]]
name: string
size: string
type: string
subtype: string
alignment: string
ac: number
hp: number
hit_dice: 8d8
speed: string
stats: [number, number, number, number, number, number]
saves:
  - <ability-score>: number
skillsaves:
  - <skill-name>: number
damage_resistances: string
senses: string
languages: string
cr: number
spells:
  - <description>
  - <spell level>: <spell-list>
traits:
  - name: <reaction-name>
  - desc: <reaction-description>
  - ...
actions:
  - name: <reaction-name>
  - desc: <reaction-description>
  - ...
legendary_actions:
  - name: <reaction-name>
  - desc: <reaction-description>
  - ...
bonus_actions:
  - name: <trait-name>
  - desc: <trait-description>
  - ...
reactions:
  - name: <reaction-name>
  - desc: <reaction-description>
  - ...
```



```statblock
image: [[https://pathfinderwiki.com/mediawiki/images/thumb/9/95/Red_dragon.jpg/250px-Red_dragon.jpg]]
name: Ancient Red Dragon (Level 35)
size: Gargantuan
type: Dragon
subtype: Fire
alignment: Chaotic Evil
ac: 45
hp: 642
hit_dice: 35d12+315
speed: 60 ft., climb 60 ft., fly 250 ft.
stats: [41, 10, 29, 26, 23, 26]
fage_stats: [35, 35, 35, 35, 35, 35, 35, 35, 35]
saves:
  - fortitude: 32
  - reflex: 22
  - will: 28
skillsaves:
  - acrobatics: 45
  - perception: 49
  - stealth: 45
  - intimidate: 49
  - bluff: 49
damage_vulnerabilities: Cold
damage_resistances: Fire (30)
damage_immunities: Paralysis, sleep
condition_immunities: Frightened, charmed
senses: Darkvision 120 ft., Blindsight 60 ft., True Seeing 120 ft.
languages: Draconic, Common, Giant, Ignan
cr: 35
spells:
  - caster level: 17
  - 9th level: Meteor Swarm
  - 8th level: Fire Storm, Incendiary Cloud
  - 7th level: Delayed Blast Fireball, Firebrand
  - 6th level: Chain Lightning, Contingency
  - 5th level: Wall of Force, Teleport
traits:
  - name: Spellcasting
    desc: The ancient red dragon is a 17th-level spellcaster. Its spellcasting ability is Intelligence (spell save DC 23, +15 to hit with spell attacks). It knows the following sorcerer spells.
  - name: Frightful Presence
    desc: Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 27 Wisdom saving throw or become frightened for 1 minute.
actions:
  - name: Multiattack
    desc: The ancient red dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.
  - name: Bite
    desc: Melee Weapon Attack: +29 to hit, reach 20 ft., one target. Hit: 23 (4d6 + 19) piercing damage and 14 (4d6) fire damage.
  - name: Claw
    desc: Melee Weapon Attack: +29 to hit, reach 15 ft., one target. Hit: 17 (2d6 + 19) slashing damage.
  - name: Tail
    desc: Melee Weapon Attack: +29 to hit, reach 20 ft., one target. Hit: 19 (2d8 + 19) bludgeoning damage.
  - name: Breath Weapons (Recharge 5-6)
    desc: The dragon uses one of the following breath weapons:
          1. Fire Breath: The dragon exhales fire in a 120-foot line that is 10 feet wide. Each creature in that line must make a DC 30 Dexterity saving throw, taking 112 (25d8) fire damage on a failed save, or half as much damage on a successful one.
          2. Weakening Breath: The dragon exhales gas in a 120-foot line that

```