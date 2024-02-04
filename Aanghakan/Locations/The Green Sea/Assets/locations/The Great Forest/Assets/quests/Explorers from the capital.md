The Stonehelm Clan, protectors of Thunderpeak, have grown increasingly concerned about the sinister transformation of the forest. Disturbing reports of grotesque creatures and cultist activities have reached their ears.

#Master-Notes The party while traversing the forest, encounters a fierce battle between the Stonehelm Clan and the cultists of the Abyssal Serpent. 


```encounter
name: Explorers from the capital
party: 2
creatures:
 - 3: Goblin
 - 1: Night Hag
 - 2: Owlbear
```

```statblock
name: Night Hag
size: Medium
type: fiend
subtype: ""
alignment: neutral evil
ac: 17
hp: 54
hit_dice: 112
speed: 30 ft.
stats:
  - 18
  - 15
  - 16
  - 16
  - 14
  - 16
skillsaves:
  - deception: 7
  - insight: 6
  - perception: 6
  - stealth: 6
damage_vulnerabilities: ""
damage_resistances: cold, fire; bludgeoning, piercing, and slashing from nonmagical weapons that aren't silvered
damage_immunities: ""
condition_immunities: charmed
senses: darkvision 120 ft., passive Perception 16
languages: Abyssal, Common, Infernal, Primordial
cr: "5"
bestiary: true
traits:
  - name: Innate Spellcasting
    desc: |-
      The hag's innate spellcasting ability is Charisma (spell save DC 14, +6 to hit with spell attacks). She can innately cast the following spells, requiring no material components:

      At will: detect magic, magic missile
      2/day each: plane shift (self only), ray of enfeeblement, sleep
    attack_bonus: 0
  - name: Magic Resistance
    desc: The hag has advantage on saving throws against spells and other magical effects.
    attack_bonus: 0
  - name: Night Hag Items
    desc: |-
      A night hag carries two very rare magic items that she must craft for herself If either object is lost, the night hag will go to great lengths to retrieve it, as creating a new tool takes time and effort.
      Heartstone: This lustrous black gem allows a night hag to become ethereal while it is in her possession. The touch of a heartstone also cures any disease. Crafting a heartstone takes 30 days.
      Soul Bag: When an evil humanoid dies as a result of a night hag's Nightmare Haunting, the hag catches the soul in this black sack made of stitched flesh. A soul bag can hold only one evil soul at a time, and only the night hag who crafted the bag can catch a soul with it. Crafting a soul bag takes 7 days and a humanoid sacrifice (whose flesh is used to make the bag).
    attack_bonus: 0
  - name: Hag Coven
    desc: |-
      When hags must work together, they form covens, in spite of their selfish natures. A coven is made up of hags of any type, all of whom are equals within the group. However, each of the hags continues to desire more personal power.
      A coven consists of three hags so that any arguments between two hags can be settled by the third. If more than three hags ever come together, as might happen if two covens come into conflict, the result is usually chaos.
    attack_bonus: 0
  - name: Shared Spellcasting (Coven Only)
    desc: |-
      While all three members of a hag coven are within 30 feet of one another, they can each cast the following spells from the wizard's spell list but must share the spell slots among themselves:

      • 1st level (4 slots): identify, ray of sickness
      • 2nd level (3 slots): hold person, locate object
      • 3rd level (3 slots): bestow curse, counterspell, lightning bolt
      • 4th level (3 slots): phantasmal killer, polymorph
      • 5th level (2 slots): contact other plane, scrying
      • 6th level (1 slot): eye bite

      For casting these spells, each hag is a 12th-level spellcaster that uses Intelligence as her spellcasting ability. The spell save DC is 12+the hag's Intelligence modifier, and the spell attack bonus is 4+the hag's Intelligence modifier.
    attack_bonus: 0
  - name: Hag Eye (Coven Only)
    desc: |-
      A hag coven can craft a magic item called a hag eye, which is made from a real eye coated in varnish and often fitted to a pendant or other wearable item. The hag eye is usually entrusted to a minion for safekeeping and transport. A hag in the coven can take an action to see what the hag eye sees if the hag eye is on the same plane of existence. A hag eye has AC 10, 1 hit point, and darkvision with a radius of 60 feet. If it is destroyed, each coven member takes 3d10 psychic damage and is blinded for 24 hours.
      A hag coven can have only one hag eye at a time, and creating a new one requires all three members of the coven to perform a ritual. The ritual takes 1 hour, and the hags can't perform it while blinded. During the ritual, if the hags take any action other than performing the ritual, they must start over.
    attack_bonus: 0
actions:
  - name: Claws (Hag Form Only)
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) slashing damage."
    attack_bonus: 7
    damage_dice: 2d8
    damage_bonus: 4
  - name: Change Shape
    desc: The hag magically polymorphs into a Small or Medium female humanoid, or back into her true form. Her statistics are the same in each form. Any equipment she is wearing or carrying isn't transformed. She reverts to her true form if she dies.
    attack_bonus: 0
  - name: Etherealness
    desc: The hag magically enters the Ethereal Plane from the Material Plane, or vice versa. To do so, the hag must have a heartstone in her possession.
    attack_bonus: 0
  - name: Nightmare Haunting (1/Day)
    desc: While on the Ethereal Plane, the hag magically touches a sleeping humanoid on the Material Plane. A protection from evil and good spell cast on the target prevents this contact, as does a magic circle. As long as the contact persists, the target has dreadful visions. If these visions last for at least 1 hour, the target gains no benefit from its rest, and its hit point maximum is reduced by 5 (1d10). If this effect reduces the target's hit point maximum to 0, the target dies, and if the target was evil, its soul is trapped in the hag's soul bag. The reduction to the target's hit point maximum lasts until removed by the greater restoration spell or similar magic.
    attack_bonus: 0

```

```statblock
name: Owlbear
size: Large
type: monstrosity
subtype: ""
alignment: unaligned
ac: 13
hp: 59
hit_dice: 54
speed: 40 ft.
stats:
  - 20
  - 12
  - 17
  - 3
  - 12
  - 7
skillsaves:
  - perception: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: darkvision 60 ft., passive Perception 13
languages: ""
cr: "3"
bestiary: true
traits:
  - name: Keen Sight and Smell
    desc: The owlbear has advantage on Wisdom (Perception) checks that rely on sight or smell.
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The owlbear makes two attacks: one with its beak and one with its claws."
    attack_bonus: 0
  - name: Beak
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. Hit: 10 (1d10 + 5) piercing damage."
    attack_bonus: 7
    damage_dice: 1d10
    damage_bonus: 5
  - name: Claws
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 14 (2d8 + 5) slashing damage."
    attack_bonus: 7
    damage_dice: 2d8
    damage_bonus: 5
```

After a long fight, the party is rewarded with an allied force to help them push through the forest.

#Master-Notes  The allied forces are a warrior and a ranger, other members of the party are dead or missing.

```statblock
name: Sir Leonard StoneHelm
size: Medium
type: dwarf
subtype: ""
alignment: NG
ac: 19
hp: 59
hit_dice: 54
speed: 40 ft.
stats:
  - 15
  - 12
  - 17
  - 9
  - 12
  - 7
skillsaves:
  - perception: 3
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 6
languages: "Common"
traits:
  - name: Shield Rise
    desc: Can use reaction to rise shield and get +2 CA against ranged attacks
    attack_bonus: 0
  - name: Secret dwarven style
    desc: Can easily switch between main weapon and a secondary weapon as part of one action or a reaction
    attack_bonus: 0
actions:
  - name: Long Sword
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: (1d10 + 2) S and P damage."
    attack_bonus: 7
    damage_dice: 1d10
    damage_bonus: 5
```

Sir Leonard is a peculiar warrior that fights with a black great sword and a huge dwarven shield. Its fight style is fruit of years of experience and of the secret arts of the dwarven people.


```statblock
name: Arya Whisperwind
size: Medium
type: half-elf
subtype: ""
alignment: CN (Chaotic Neutral)
ac: 16 
hp: 45
hit_dice: 5d10
speed: 35 ft.
stats:
  - 10
  - 18 
  - 14 
  - 12 
  - 15 
  - 11 
skillsaves:
  - stealth: +8
  - perception: +6
  - survival: +6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Perception 16
languages: "Common, Elvish"
traits:
  - name: Keen Senses
    desc: Has advantage on Perception checks relying on sight, hearing, or smell
  - name: Fleet of Foot
    desc: Can move stealthily at a normal pace
  - name: One with the shadows (Stealth ring)
    desc: Can become invisible if at least partially obscured and still for at least a couple seconds
actions:
  - name: Longbow
    desc: "Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. Hit: (1d8 + 4) piercing damage."
    attack_bonus: 7
    damage_dice: 1d8
    damage_bonus: 4
  - name: Short Sword
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: (1d6 + 4) piercing damage."
    attack_bonus: 7
    damage_dice: 1d6
    damage_bonus: 4

```

Arya's high Dexterity and proficiency in Stealth make her an excellent scout. Use her to gather information about enemy positions, traps, and terrain before engaging in combat. Her "Fleet of Foot" trait allows her to move quickly and silently, ideal for reconnaissance.
