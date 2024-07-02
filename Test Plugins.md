[init tracker](obsidian://show-plugin?id=initiative-tracker)
[statblocks](obsidian://show-plugin?id=obsidian-5e-statblocks)

# TITOLO

[[Test Plugins#]]

```encounter
name: Example encounter
party: 2
creatures:
 - 3: Goblin
```
  

```statblock
image: [[Wikilink To Image]]
name: Elite Kobold Warrior
size: small
type: Humanoid
subtype: Kobold
alignment: Lawful Evil
ac: 17
hp: 65
speed: 30 ft.
stats: [14,16,16,8,12,9]
senses: Darkvision 60 ft., passive Perception 14
languages: Draconic
challenge: 4 (1,100 XP)
actions:
  - name: ba
    desc: bebe
traits:
  - name: bubu
    desc: caca
  - name: xpsilon
    desc: work pls
traits+:
  - name: cucu
    desc: mumu
```

  - name: Pack Tactics
  - desc: The kobold has advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't incapacitated.
  - name: Ambush Leader
  - desc: The kobold can guide its allies in setting up an effective ambush, granting them a +2 bonus to their initiative rolls if they are part of the ambush.


```statblock
name: Infernal Emissary
size: Large
type: Fiend
subtype: Devil
alignment: Lawful Evil
ac: 18
hp: 200
hit_dice: 16d10 + 112
speed: "30 ft., fly 60 ft."
stats: [22, 14, 24, 17, 15, 20]
saves:
  - dexterity: 7
  - constitution: 12
  - wisdom: 7
  - charisma: 10
skills: 
  - deception: 10
  - intimidation: 10
damage_resistances: "Cold; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks that aren't Silvered"
damage_immunities: "Fire, Poison"
condition_immunities: "Poisoned"
senses: "Truesight 120 ft., Passive Perception 12"
languages: "Infernal, Common, Telepathy 120 ft."
cr: 11
traits:
  - name: Infernal Command
    desc: "Can command lesser devils and demons within 60 feet as a bonus action."
  - name: Dark Pact
    desc: "Telepathic bond with its Warlock master, allowing them to communicate over any distance on the same plane of existence."
  - name: Abyssal Flames
    desc: "Melee weapon attacks deal an extra 10 (3d6) fire damage on a hit."
  - name: Magic Resistance
    desc: "The devil has advantage on saving throws against spells and other magical effects."
  - name: Spellcasting
    desc: "The devil is a 10th-level spellcaster. Its spellcasting ability is Charisma (spell save DC 18, +10 to hit with spell attacks). It has the following warlock spells prepared: Cantrips (at will): Eldritch Blast, Minor Illusion; 1st-5th level (3 5th-level slots): Hex, Hold Monster, Fireball, Dimension Door, Wall of Fire."
actions:
  - name: Multiattack
    desc: "The devil makes three attacks with its infernal glaive."
  - name: Infernal Glaive
    desc: "Melee Weapon Attack: +11 to hit, reach 10 ft., one target. Hit: 15 (2d8 + 6) slashing damage plus 10 (3d6) fire damage."
challenge: 11 (7,200 XP)
```



hello gpt could you describe very powerful undead enemies for dnd campaign? They are the "skullies" undead pirates under the service of Lich Beard : I need something that can challenge a party of 5 people. The skullies are literally normal humanoids but cursed (like pirates of the Caribbean) so the sets of skills should be "player like". Also I need you to focus on the feats and actions (put spells in actions to simplify) from dnd 5e and fill out this as a form ```statblock 
image: [] 
name: Enemy_Name 
string size: "Small" | "Medium" | "Large" 
type: Enemy_Type string 
subtype: Enemy_Subtype 
string alignment: Enemy_Alignment "LE" | "CE" .... (caotic, legal, neutral, good, evil....) 
ac: Enemy_AC number 
hp: Enemy_HP number 
speed: Enemy_Speed string(+"mt") 
stats: [STR, DEX, CON, INT, WIS, CHA] 
saves: - Fortitude : Enemy_Fort number - Reflex : Enemy_Reflex number - Will : Enemy_Will number 
skillsaves: - Climb: +4 - Intimidate: +7 - Perception: +3 damage_vulnerabilities: Fire 
traits: - name: Multiattack desc: The Bear makes two attacks. - name: Iron Will desc: The Bear has advantage on saving throws against being frightened... - name: Corrupted Charge desc: If the Corrupted Bear moves at least 9mt straight toward a target and then hits it with .... - name : Example string desc : Example_test string 
actions: - name : Bite desc : Melee Attack +8 to hit, 1d8 + 5 piercing damage. - name : Claws desc : Melee Attack +8 to hit 2d6 + 5 slashing damage. - name : Example string desc : Example_test string ```


```statblock
image: []
name: Skully Raider
size: Medium
type: Undead
subtype: Pirate
alignment: CE (Chaotic Evil)
ac: 17
hp: 75
speed: 30ft
stats: [16, 14, 16, 12, 11, 13]
saves:
  - Fortitude: +5
  - Reflex: +4
  - Will: +3
skillsaves:
  - Acrobatics: +5
  - Intimidation: +4
  - Perception: +4
damage_vulnerabilities: b
traits:
- name: Multiattack
  desc: The Skully Raider makes two weapon attacks.
- name: Undead Fortitude
  desc: If damage reduces the Skully Raider to 0 hit points, it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is fire or radiant. On a success, the Skully Raider drops to 1 hit point instead.
- name: Cursed Blade
  desc: Any melee attack made by the Skully Raider is considered magical for the purpose of overcoming resistance and immunity to nonmagical attacks and damage.
- name: Fearless Marauder
  desc:  The Skully Raider must be under fullmoon light to benefit from this trait. The Skully Raider has advantage on saving throws against being frightened and can move through other creatures and objects as if they were difficult terrain. It does not provocate attacks of opportunity but takes 1d4 force damage if it ends its turn inside an object.
actions:
  - name: Cutlass Slash
    desc: Melee Weapon Attack +6 to hit, reach 5 ft., one target. Dmg 1d6 + 4 slashing damage plus  1d8 necrotic damage.
  - name: Pistol Shot
    desc: Ranged Weapon Attack +5 to hit, range 30/90 ft., one target. Dmg 9 1d10 + 4 piercing damage. The Skully Raider can't use Pistol Shot again until it completes a short or long rest.
  - name: Throwable net
    desc: Ranged Weapon Attack +5 to hit, reach 10 ft., one target. Dmg 1d4 damage, and the target is grappled (escape DC 15). The Skully Raider can't use this ability again until it completes a short or long rest.
```

```statblock
name: Frostfire Drake
size: Huge
type: Dragon
subtype: Elemental
alignment: Neutral
ac: 19 (Natural Armor)
hp: 230 (20d12 + 100)
speed: 40 ft., fly 80 ft.
stats: [24, 12, 21, 16, 14, 18]
saves:
  - strength: +11
  - constitution: +10
  - wisdom: +7
  - charisma: +9
skillsaves:
  - perception: +10
  - stealth: +5
damage_resistances: Fire, Cold
damage_immunities: Fire, Cold
condition_immunities: Charmed, Frightened
senses: Darkvision 120 ft., Passive Perception 20
languages: Draconic, Common
cr: 16
traits:
- name: Frostfire Aura
  desc: At the start of each of the drake's turns, each creature within 10 feet of it takes 10 (3d6) fire damage and 10 (3d6) cold damage, and flammable objects in the aura that aren't being worn or carried ignite.
- name: Ice and Fire Breath (Recharge 5-6)
  desc: The drake exhales a blast of frostfire in a 60-foot cone. Each creature in that area must make a DC 19 Dexterity saving throw, taking 70 (20d6) fire and cold damage on a failed save, or half as much damage on a successful one.
- name: Legendary Resistance (3/Day)
  desc: If the drake fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The drake makes three attacks: one with its bite and two with its claws.
- name: Bite
  desc: Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 19 (2d10 + 8) piercing damage plus 9 (2d8) fire damage and 9 (2d8) cold damage.
- name: Claw
  desc: Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 15 (2d6 + 8) slashing damage.
legendary_actions:
- name: Detect
  desc: The drake makes a Wisdom (Perception) check.
- name: Wing Attack (Costs 2 Actions)
  desc: The drake beats its wings. Each creature within 10 feet of the drake must succeed on a DC 21 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning damage and be knocked prone. The drake can then fly up to half its flying speed.
```

https://discordjs.guide/preparations/adding-your-bot-to-servers.html#creating-and-using-your-invite-link