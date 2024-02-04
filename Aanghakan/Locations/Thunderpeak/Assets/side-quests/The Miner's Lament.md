
[[Filip and Ki|Filip]], the foreman of the Crystal Caves, is in a bind. Not only have there been mysterious cave-ins spooking his miners, but now an infestation of exploding rats, seemingly originating from deeper within the caves, is jeopardizing operations. [[Filip and Ki|Filip]] needs you to investigate and deal with these problems before panic spreads among his crew. Also it seems that his partner in business, [[Filip and Ki|Ki]] has gone missing in the mines. 

As you delve deeper into the caves, you may discover that the rats are not naturally explosive but have been corrupted by what appears to be a parasite. You also find out that the cave-ins and the rat infestation are not unrelated. The disturbances in the cave structure seem to have agitated the normally passive rats, which seem to trigger explosions in random portions of the galleries. 

Several puzzles can be involved in this quest:

1. **The Mine Map Puzzle:** To navigate the sprawling caves, the party will need a map. Getting one should be easy enough...
2. **The Crystal Resonance Puzzle:** Certain formations of crystals in the cave walls seem to be able to pacify the rats when they resonate at a certain frequency, while making them explode at other frequencies. The party needs to figure out how to replicate this resonance to create safe passage through areas thick with the explosive vermin and to rescue [[Filip and Ki|Ki]]. Maybe a critical miss could turn into an opportunity... 

The quest will culminate in the revelation that [[Filip and Ki|Filip]] has betrayed the city in exchange of favorable treatment by the cultists, and also suspects that he could be a member himself. 

>  *Filip* : That **darn** dwarf and his fixation to dig. I **specifically** told him not to dig in the direction of the [[Crystal Caverns]], but **NOOO**. He **had to**, and now he's missing. 

```statblock
image: [[Enchanted Armor Image Link]]
name: Corrupted Rat
size: M
type: Corrupted beast
subtype: Rat
alignment: (Align:NE)
ac: 19
hp: 21
speed: 9mt
stats: [13, 18, 14, 12, 12, 10]
saves:
  - Fortitude : 5
  - Reflex : 3
  - Will : 1
skillsaves:
  - climb : +4
  - Acrobatics : +4
damage_vulnerabilities: Fire 

traits:
- name: Darkvision
- desc: The Corrupted Rat can see in the dark within a specific radius.
- name: Keen Smell
- desc: The Corrupted Rat has advantage on Wisdom (Perception) checks that rely on smell.

actions:
- name : bite
- desc : The rat can bite +3 to hit, 1d4+2
- name: Screech
- desc: The Corrupted Rat emits a high-pitched screech. Each creature within 10 feet of it that can hear it must succeed on a DC 12 Constitution saving throw or be stunned for 1 turn. If any rats are within 100mt they will be attracted to the fight.

```
