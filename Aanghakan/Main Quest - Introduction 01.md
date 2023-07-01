
The chosen of [[Elune]], a legendary warrior destined to defend the world in its darkest times. 

Legends talk about [[Aein]], curator of the [[animus]], first of [[The Chosen|the chosen]], born of the [[Giants]], and how he defeated [[Goor]], king of the Orcs, and his vast armies of chaos. Then is [[Thein]] the second chosen, born among wolves, pure of soul, untarnished, bearer of the [[thousand roots]]. Then is [[Yaohwan]], born of Valkyrie blood, third of the chosen, protector of the people, wise diplomat and architect of the unity in [[Aanghakan]]. He died, thousands of years in the past, leaving a legacy of peace and hope.

But while hope yields prosperity, evil is *always* capable of seeping through the smallest gaps, corrupt the meek, build upon the dark desires of the ones left behind.

Our story begins in the small town of [[Esmeralda]], jewel of boundless pastures, lodged in the plains of the [[Green Sea]], near [[Thunderpeak]].
Our party of yet to be heroes has just completed an humble request of the local tavern owner of moving a shipment of beer and various foods and alcoholic beverages. It appears that our heroes have some kind of basic accommodation at said tavern, "The Stubborn Ol'Mule": in exchange of simple services and mansions they are given room and board from the old owner, which has slowly reached senile age but has made enough to send his son to study smiting at the capital, and thus needs a little hand once in a while.

<hr>

#Master-Notes
In this section I'll present a couple notes for the master, as in the world building some elements must be necessary in order to maintain a coherent story, while allowing you to create your own world.

<span style="background-color:lightblue;color:black;"> !important </span> 
Main quest - The following person should be introduced as soon as possible, as it will be the main NPC (or played by someone special) of the quest. Serene, daughter of a retired human warrior [[Hank]] and of an half elf from the [[East O'lands]] which is known as the land of the elves. Rumor has it that her mother may be of noble blood due to the her silver hair, but she left early due to an unknown illness so not much is actually known. She's (not yet) the next chosen of Elune and, despite her current lack of power, she will be accompanying the party in the initial stages of her journey.

Previous knowledge - the players know the following things about the area:

- [[Esmeralda]] #bLocation is the southernmost village in the [[Erebor|region]], several days from [[Thunderpeak]] and closest to the [[Great Forest]]. 
- The small town has the following features : a *small market* where pelts and grains are exchanged for trinkets and weapons from the capital, a *town square* with a bulletin board and a *town hall*, and a *small church* nearby with a fountain and a statue dedicated to [[Yannee]], sister of Elune.
- The town's main productions are grains and vegetables. Hunters who live nearby also trade goods in exchange for pelts, bones, and meats.
- The townsfolk are preparing for the traditional spring festivities, and people from nearby settlements are coming to enjoy the nightly party.

<hr>


The players are then introduced to what they know about the area and the culture and are free to explore the busier than usual town.

When the players get to the town square they can overhear an animate discussion between a merchant and a known hunter of the area, [[Hank]]. The discussion seems about a missed deadline of an important shipment of exotic pelts for the capital.

>Hank: My deepest apologies, sir. 
>Merchant: I CAN'T BELIEVE... 
>Hank: Please, sir, allow me to explain. I've said it numerous times - the animals seem to have wandered off. 
>Merchant: IMPOSSIBLE. Animals don't just vanish; they're hunted and their pelts are sold. Who has my pelts? WHO? FOR WHAT PRICE? 
>Hank: Sir, I assure you... If you could give it just a couple more days... 
>Merchant: ... Hank, you're in the dark. If I miss _HER_ birthday, my fate is sealed! You're essentially advising me to savor my final days on Earth.

#Master-Notes If players ignore the conversation, they will be later met by Serene that will hint at [[Hank]], mentioning the return of a favor the hunter did for the party. If it fails, let them enjoy the bustling town and its attractions, they will be later met by [[Hank]] himself that will propose a job for the team.

<hr>

## The Great Forest

The sun filters through the dense leaves of the Great Forest, casting dappled shadows over the party as they follow [[Hank]] through the verdant undergrowth. From the sprawling trees to the flowering ferns, the forest is an orchestra of nature's bounty. But for all its beauty, the forest lies eerily silent today.

As you push deeper into the forest, you find numerous tracks of all sorts of creatures. However, something feels off. Tracks lead into dead ends, or loop back onto themselves in a confusing maze of steps, and yet, not a single animal in sight. Despite the abundance of evidence of animal activity, the forest feels unnervingly devoid of life.

Trekking through the undergrowth with Hank, you notice his usual light-hearted demeanor is tainted by frustration and restlessness. "Should have been feet-up, enjoying the day," he grumbles, shooting a resentful glance towards the forest's depths. "But *no*, it had to be one of *those* days", punctuating his sentiment with a contemptuous spit to the ground.

Suddenly, after several hours of search, a low growl can be heard echoing from a distance, followed by the sound of grunting and the metallic scraping of a cage. As you cautiously investigate, you come upon a sight that chills your bones - a group of explorers, their cloaks adorned with the sigil of the [[Abyssal Serpent]], standing before an enormous cage. Inside, a bear paces restlessly, its anxious eyes reflecting the surrounding firelight.
One of the cultists begins a quick chant, and with a waive of the hand the bear suddenly drops. The other cultist quickly finish up preparing some sort of ritual around the cage

#Master-Notes 
This is the critical moment where the players can interfere with the ritual and attack the explorers or plan to follow them back to the cultist's camp. 

Should the players choose to intervene, a battle will ensue, offering them the first real taste of the sinister plot they are about to uncover: as the players attack, one of the cultists will offer up his life in order to complete the ritual and the bear will suddenly start to morph into a monstrosity and attack the players.

> Cultist : Slithering vermin, I'll show you true despair. Complete the ritual my brethren.

If they chose to ignore, the cultist will lead the party to a deep part of the forest where some hostages are kept, and the ritual will ensue. 

If they opt to hold back, the cultists will lead the party to a secluded part of the forest where hostages are held, and the ritual will proceed.

As [[Hank]] recognizes one of his hunting partners among the hostages, the encounter begins:

```encounter
name: Encounter in the forest
creatures:
 - 2: Cultist
 - 1: Corrupted Bear (150 XP)
```

```statblock
image: [[https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/2010-kodiak-bear-1.jpg/1200px-2010-kodiak-bear-1.jpg]]
name: Corrupted Bear
size: Medium
type: Corrupted beast
subtype: Void
alignment: (Align:CE)
ac: 17
hp: 37
speed: 9mt
stats: [20, 13, 16, 8, 8, 14]
saves:
  - Fortitude : 7
  - Reflex : 3
  - Will : 1
skillsaves:
  - Climb: +4
  - Intimidate: +7
  - Perception: +3
damage_vulnerabilities: Fire 

traits:
- name: Multiattack
- desc: The Bear makes two attacks.
- name: Iron Will
- desc: The Bear has advantage on saving throws against being frightened.
- name: Corrupted Charge
- desc: If the Corrupted Bear moves at least 9mt straight toward a target and then hits it with a claw attack on the same turn, the target takes an extra (2d6) slashing damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be knocked prone.

actions:
- name : Bite
  desc : Melee Attack +8 to hit, 1d8 + 5 piercing damage.
- name : Claws
  desc : Melee Attack +8 to hit 2d6 + 5 slashing damage.

```


```statblock
image: [[https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/2010-kodiak-bear-1.jpg/1200px-2010-kodiak-bear-1.jpg]]
name: Cultist
size: Medium
type: Cultist of the Abyssal Serpent
subtype: Human
alignment: (Align:CE)
ac: 16
hp: 22
speed: 9mt
stats: [8, 12, 14, 16, 14, 14]
saves:
  - Fortitude : 1
  - Reflex : 2
  - Will : 6
skillsaves:
  - Perception: +3

traits:
- name: Toughness
  desc: Gain +3 hit points. For every Hit Die you possess beyond 3, you gain an additional +1 hit point.
- name: Weapon Focus
  desc: Gain +1 bonus on all attack rolls you make using the selected weapon (Dagger).
- name : Eschew Materials
  desc : You can cast any spell that has a material component costing 1 gp or less without needing that component.
actions:
- name : Dagger Strike
  desc : Melee Attack +8 to hit, 1d4 + 2 piercing damage.
- name : Corrupted Touch
  desc : Melee Spell Attack +8 to hit, 2d6 + 3 necrotic damage.

spells:
- name: Acid Splash - 1d6 acid damage (cantrip).
- name: Darkness - 6mt radius of supernatural shadow.
- name: Magic Missile - 1d4 damage that cannot be avoided.


```

#Master-Notes
The encounter may be avoided and not strictly necessary, but I'd advise against not letting the players find the following document.


<hr>


Hidden amongst the cultist's personal effects, the party uncovers a unsettling letter:

>To the Faithful of the Abyssal Serpent,
>
>Our years of dedication and sacrifice are about to bear fruit. The army we have painstakingly amassed stands ready, a testament to our unwavering devotion to the Abyssal Serpent. The final pieces of our grand plan have fallen into place. The last of the beasts have been captured and transformed into void beings, their essence twisted to serve our divine purpose.
>
>The march to the capital is imminent. Our forces, bolstered by the might of the void beasts, are unstoppable. The city's defenses will crumble before us, and the _Hearth_ of the city will beat in rhythm with our cause, and its pulse will echo the glory of the Abyssal Serpent.
>
>Let this letter serve as a reminder of our purpose and the destiny that awaits us. We are not mere followers; we are the chosen ones, the harbingers of a new era. Our actions will shape the future, and in the Abyssal Serpent's name, we will usher in a reign of darkness that will last for eternity.
>
>Stay steadfast, my brothers and sisters. The dawn of our victory is near.
>
>By the serpent's will,
>
>Yggdrasil of the [[Cult of the abyssal serpent|scaled shield]].
>

The cultist encampment is a trove of goods — pelts, rations, and beyond the mundane, weapons, enchanted components...

> _Hank:_ This is an omen... I've got a sick feeling about what's coming next.

The moment the party decides to go back, it's late afternoon and the festivities have just begun. Returning to the village will take at least 2 hours of forced march and players will be fatigued by the time they reach destination.

As you make your way back to Esmeralda, the distant sounds of music and laughter gradually grow louder. As you enter the village, you find it bustling with activity and adorned with colorful decorations in preparation for the spring festivities. The town is nestled in a picturesque setting, surrounded by lush green fields and gentle rolling hills, filled with stands and people of all sorts.

The cozy market square buzzes with life, vendors and merchants showcasing their various wares. Stalls are filled with various goods, from fresh grains and vegetables harvested from the local fields to pelts, bones, and meats brought by the hunters. The air is filled with the aroma of delicious food being cooked, tempting your senses. 

The townsfolk have gathered in the town square, their attention focused on a makeshift stage. A middle-aged man, dressed in fine attire, steps forward to address the crowd. It is Mayor Thomas, a respected figure in Esmeralda known for his eloquence and unwavering dedication to the community. Mayor Thomas raises his hands, signaling for silence. The vibrant energy of the crowd gradually subsides as all eyes turn toward him. With a warm smile, he begins his speech, his voice carrying across the square.
"Good people of Esmeralda, esteemed guests, today we gather not only to celebrate the changing of seasons, but also to express our gratitude for the bountiful harvest that awaits us." His words resonate with hope and optimism, infusing the air with a sense of unity.

Yet, at the very crescendo of Mayor Thomas's rousing speech, a guttural roar pierces the air, cutting through the jubilant atmosphere like a knife. The crowd falls into a stunned silence as a monstrous shadow engulfs the stage. In an unforeseen, grisly turn of events, a mutant owl bear, its size grotesquely enlarged, bursts into the square with terrifying speed. Mayor Thomas's eyes widen in terror as he raises his arms instinctively to shield himself, but before he can react, the mutant creature strikes with savage ferocity. In a gruesome instant, the owl bear's razor-sharp claws rip through the air, severing Mayor Thomas's head from his body. Shock and horror ripple through the crowd, followed by a wave of panic and pandemonium.

People scream and scatter in all directions, their screams piercing the night, desperately seeking safety from the nightmarish aberration that now rampages through the square. The once-celebratory atmosphere dissolves into chaos as the mutated creatures from the forest emerge. Their forms are grotesque, twisted by forbidden rituals, they tear through flesh and bone mercilessly.

[[Hank]], driven by sheer determination, pushes through the frantic crowd, his eyes scanning desperately for Serene. The players, caught in the midst of the chaos, find themselves unable to fight or take immediate decisive action. The overwhelming panic paralyzes their ability to react, forcing them to witness the unfolding carnage as the beasts from the forest wreak havoc upon the defenseless villagers.

#Master-Notes Here you should discuss with the party what is their plan to get out alive. 

Amidst the chaos, a solitary black figure can be seen slipping through the crowd of people, moving with an eerie grace, seemingly unaffected by the presence of those around it, towards the town's church. Despite the chaos and commotion, its advance is unhindered, almost as if it was death itself.

Your players arrive at the scene just in time to witness the cloaked figure reveal herself. She's a young drakonoid, her scales glistening in the moonlight and eyes ablaze with an unholy fervor. As she catches sight of Serene, her lips curl up into a sinister smirk.

Serene is in the midst of guiding the frightened children onto a carriage, her eyes darting anxiously between them and the pandemonium in the square. The drakonoid swiftly closes the distance between them, her movements unnaturally swift and fluid.

Before anyone can react, the drakonoid draws a wickedly curved dirk from her cloak. With a swift and precise motion, she plunges it into Serene's chest. There's a gasp, a choked cry of disbelief, and Serene drops into the fountain, her lifeblood draining into the water around her.

Hank, witnessing this horrific act from the edge of the square, unleashes a resentful roar. Grief and rage twist his features as he charges at the drakonoid, his hand reaching for the weapon at his belt.

The figure calmly turns around and says with a soft voice :

> *?????* : Here comes the noble knight.

With a swift, practiced motion, she slashes open Hank's throat.

This time, the players attract the attention of the enigmatic figure, a sense of curiosity gleaming in her draconic eyes. Her words are meticulously chosen, each phrase delivered with a careful, deliberate demeanor. She exudes an aura of calculated control, every subtle inflection of her voice underscoring her formidable power.

> *?????* : And who are you supposed to be...

#Master-Notes The figure is [[Vespera Shadowdancer]], renowned assassin of the Serpent's Cult. Her task is currently to track down and extinguish the bloodline of [[Aein]], preventing the resurrection of the chosen of Elune. It's crucial to convey her overwhelming power to the players; Vespera should never appear threatened. In the face of any belligerence, she has a handy Sleep spell at her disposal.
After answering some of the possible questions the party may have, [[Vespera Shadowdancer|Vespera]] presents an ultimatum. The lives of the party in return for the children stowed away in the wagon.

#Master-Notes Among the children, one wears refined clothes and has a silver pendant that holds a picture of a duchess with her child, check [[Missing Child|missing child]] quest.

<span style="background-color:lightblue;color:black;"> !important </span> Here you should come up with what happens, as it should be role-played according to your group's sensitivity.

[[Vespera Shadowdancer|Vespera]] possesses an arsenal of spells to toy with the party and delights in reveling in the despair and dread she instills in her pawns.

```statblock
image: [[https://vespera-shadowdancer-portrait.jpg]]
name: Vespera Shadowdancer
size: Medium
type: Assassin
subtype: Drakonoid
alignment: (Align:NE)
ac: 24
hp: 150
speed: 9mt
stats: [15, 20, 16, 18, 18, 22]
saves:
  - Fortitude : 8
  - Reflex : 10
  - Will : 9
skillsaves:
  - Perception: +12

traits:
- name: Quickened Spellcasting
  desc: Vespera can cast one spell of 2nd level or lower as a bonus action.
- name: Shadowy Evasion
  desc: If Vespera is subjected to an effect that allows her to make a Dexterity saving throw to take only half damage, she instead takes no damage if she succeeds on the saving throw, and only half damage if she fails.
- name: Serpent Cult Assassin
  desc: Vespera gains +2 bonus on attack rolls against targets from the Aein's bloodline.

actions:
- name : Dagger of the Night
  desc : Melee Attack +10 to hit, 1d4 + 6 piercing damage, plus 2d6 poison damage.
- name : Shadow Blast
  desc : Ranged Spell Attack +12 to hit, 3d8 + 4 necrotic damage.

spells:
- name: Sleep - Puts creatures of up to 30 total hit points into a magical slumber for 1d4+1 turns.
- name: Darkness - 9mt radius of supernatural shadow.
- name: Telekinesis - Can push medium creatures up to 10 mt in any direction

```

## The awakening

> *????* : This is getting boring. \*\*brings a player prone and points the dagger to his face\*\*  
> ???? : Any last words?

Just as Vespera looms over one of your players, ready to deliver the final blow, a searing radiance breaks forth from the heart of the fountain, exploding like a newborn star, its light washing over the pandemonium-stricken square. All, including Vespera, recoil as their gaze is drawn towards this spectacle. Even the vicious onslaught of the abyssal creatures momentarily wavers.

As the light ebbs away, a figure crystallizes from the fountain. It's Serene, but transfigured. Her being is now otherworldly, transcending the confines of mortality. She is haloed in an aura of resplendence, a beacon of hope against the nightmare that had descended upon the village. The fatal wound that had her felled is gone. She is divine, celestial a child of the cosmos endowed with the power of Elune.

Serene has awakened as the chosen of Elune. Her presence is like the calm before a storm - tranquil yet brimming with boundless energy. Extending her hand, she conjures a staff from thin air. It pulsates with the same radiant light enveloping her, embellished with Elune's emblem. The sheer magnitude of her presence reverberates through the space, humbling even the mighty Vespera

Her words echo throughout the square, drawing the attention of all present.

> _Serene_ : By the ancient wisdom of the seers of the cosmos and the unbroken lineage of the Giants. I am the chosen of Elune, daughter of Aein. I command thee, return to the shadowy abyss from whence you came, foul spawn of darkness!"

With a commanding sweep of her staff, a storm of celestial energy roars towards Vespera. It's an attack of divine proportions, reminiscent of the wrath of a Valkyrie, a spectacular display of celestial might. Vespera, a seasoned killer, barely has time to react as the sudden transformation of Serene takes even her by surprise and it sends a chill of fear down her spine. She tries to maintain her composed facade, but her eyes betray a spark of panic.

Realizing she's outmatched, Vespera opts for retreat. Her hands move in a flurry, tracing the arcane symbols in the air. A portal of shadow and smoke erupts from the ground, its swirling vortex consuming all light around it.

With a majestic wave of her star-forged staff, Serene sends a maelstrom of divine energy screaming towards Vespera. The drakonoid barely clears the portal as the storm crashes into it, a blinding explosion of light and power that washes over the square, leaving nothing but the stench of singed scales and a palpable dread hanging in the air.

The aftermath of the spectacle is almost eerily serene. The chaos that had once engulfed the village seems a distant memory as the avatar of Elune stands in the heart of the square, the radiant glow of her presence pushing back the darkness.

She turns her gaze to the party, a wise and ancient light burning in her eyes. Her voice is soft, yet it carries an undeniable authority as she speaks:

> _Elune_ : "Children of Esmeralda, you have witnessed the evil that has taken root in this land. My chosen one, Serene, is the beacon of hope against this rising tide of chaos. She carries within the power to turn the tides, but she cannot do it alone. 
> I beseech you to protect my daughter, guide her, help her fulfill her destiny. 
> Journey with her to Thunderpeak, seek out a man named [[Odin the Wise]]. He will guide you further."

As the goddess's words fade, her celestial form begins to dissipate, the radiant aura shrinking back and Serene collapses to the ground, her body frail and unconscious after the divine possession.

Reality sets in as the beasts continue the rampage, leaving no choice but to leave...
