# Design overview
This document outlines the general design goals and philosophy behind Wasteland Tactics.

Simple games are fun and easy to learn, but quickly turn boring. Complex games are engaging but difficult to learn, and impose a lot of mental overhead. The best games have fundamentally simple rules which interact in complex ways, providing the best of both worlds. Wasteland Tactics aspires to this ideal by adhering to these basic design principles:

### Simple rules, complex interactions
Simple, general, and flexible rules are always preferred over complicated, detailed, unique rules. Wasteland Tactics' rules are basic and few in number, but they combine together in complex ways to produce deep and interesting gameplay.

### Minimize dice rolling
Every die should matter, so you don't need to roll a whole ton of them to accomplish anything. By using simplified unit and weapon profiles that interact with each other, dice rolling can be kept to a minimum. For example, attacking should use one die (with combined hit/damage effects) and defending should use one die (with combined toughness/armor/cover effects), and so on. Die re-rolls should be all but eliminated.

### Keep it real
If a game's ability to represent its source material breaks, players don't feel engaged. Wasteland Tactics is a simulation of battle and should feel like it!  Models should act like fallible soldiers with psychology. Vehicles should grind forward until quickly knocked out by heavy weapons. Monsters and tanks should inspire fear in the infantry facing them. Heavy firepower should pin down units, and the bloodiness of melee combat should drive the losers back towards safety or break them entirely.

---

# What to avoid
Wasteland tactics tries to avoid the following problems, which can plague other wargames:

### Confused scale (squad vs platoon vs company)
- It's easy to scale up simplicity, but hard to scale down complexity
- Avoid the lure of power creep, which tends to increase the scale
- Avoid adding models that are too strong or too weak for the targeted scale

### Alpha strike/First turn victory
- Use alternating unit activation rather than alternating player activation
- Minimize the possibility of first-turn charges
-- Avoid "Rhino Rush" (see below)
-- Require long distance between initially deployed forces
-- Minimize movement buffs and multipliers
- Ensure that most of an army's guns won't be within range on the first turn
- Terrain and cover should be strongly protective and block line of sight

### Morale/Leadership/Will/whatever doesn't matter
- Include a suppression/pinning system that degrades unit performance as they fail morale tests
- Make units pass a roll before being able to do anything tactically challenging (fall back from combat, split fire, shoot at a distant target, etc)

### Deathball units
- Limit the ability of models in a unit to repair damage/regain wounds
- Limit the bonuses granted by support characters--in particular, durability bonuses
- Limit the number of layers of durability and buffs to them
- Don't have "invulnerable saves"
- Make sure that support characters retain some vulnerabilities (e.g. don't allow them to join units such that they can no longer be sniped)

### Tanks are invulnerable
- Make tanks vulnerable to close combat attacks
- Make anti-tank grenades fairly prevalent among units
- Make dedicated anti-tank weapons destroy tanks very very quickly
- Make sure not to go overboard and fall victim to...

### Tanks feel like they're made of tissue paper
- Any weapon able to destroy a tank with a single lucky shot should be rare and expensive
- Don't include multiple methods of destroying tanks (e.g. wounds/hull points and also a damage table)
- Don't allow the metagame to shift in such a manner that anti-tank weapons predominate because heavy tanks are too useful, or because heavy infantry are too popular
- Make anti-tank weapons quite expensive so people won't take them to the exclusion of lighter weapons... but then of course you have to make them deadly to tanks so they're worth taking

### Tanks don't feel like tanks
- Armored vehicles should be impervious to small arms
- Anti-tank weapons should be able to score devastating hits rather than just annoyingly plinking off small numbers of wounds
- Include some kind of tank shock/overrun mechanic
- Destroyed vehicles should explode or remain on the table as wrecks

### Transport vehicles are useless
- Make sure that carried troops are significantly slower on foot
- Don't overprice transports, even if they're really good

### Vehicle-borne assault dominates the game
- Don't make transports fast enough that they can get across the table in one round
- With few exceptions, don't allow troops to make charge moves after disembarking
- Price transports correctly; cheap transports should be vulnerable and easy to kill, and high quality transports should be expensive
- Deal damage to embarked troops when their transport is destroyed

### Shooting dominates the game
- Make area terrain and intervening units block line of sight
- Terrain and cover should be strongly protective
- Ensure that speed enhancements like transport vehicles and ambush tactics work properly
- Limit the range and power of common guns and make really powerful and/or long range guns rare and expensive
- Give close combat a distinct tactical role and make it yield high rewards commensurate with its high risk

### Close combat dominates the game
- Don't implement any kind of "sweeping advance" mechanic
- Don't make infantry and dedicated close combat troops too fast
- Don't allow units to lock down shooting to an excessive extent
- Make assault an action that must be taken in lieu of something else, rather than a free thing you can just always do

### Close combat is an annoying, drawn-out tarpit
- Make close combat push the loser backwards; make that the whole point
- Allow units to voluntarily withdraw from combat, but with some kind of penalty or difficulty of accomplishing it

### Games on the inevitable terrain-poor boards suck
- Limit the range and power of common guns and make really powerful and/or long range guns rare and expensive
