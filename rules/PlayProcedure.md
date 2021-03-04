# Play Procedures

## Turn-based Procedures

### Overloaded Encounter Die

_Original Idea from Necropraxis : [Overloading the encounter die](http://www.necropraxis.com/2014/02/03/overloading-the-encounter-die/), and various refinements from around the OSR online communities_

Play in this OSR Game is based around time and resources management, and this is represented by turn-based procedures for combat, dungeon exploration and wilderness exploration. Resource management is represented as a number of turns between which players must spend those resources (food, water, light, etc.) or face varying penalties to their group during exploration.

To simplify accounting, this game replace and merges the random encounter roll and fixed duration for each resource with an overloaded encounter die, rolled at the start of each turn, which will determine what initial situation the players need to handle before continuing their voyage. Here is the basic of this overloaded die:

###### Table X: Overloaded Encounter Die template

|Die Face| Event| Precision|
|:-:|:--|:--|
|1|Encounter| The Referee rolls a random encounter appropriate for the current milieu.|
|2|Environment Effect| The Referee rolls an environment effect appropriate for the current milieu (Omen of the next encounter in a dungeon, Change of weather in the wild or at sea, etc.)|
|3|Forced Rest| The players must take the current turn to rest and consume food and water.|
|4|Waning Resources| The players must reignite their light source (either a new torch, or another dose of oil), and Spell Effects end.|
|5|Free Turn| Nothing specific happens, the players can simply continue their exploration unhindered.|
|6|Good Encounter| The Referee rolls a good random encounter appropriate for the current milieu (Helpful NPC, Secured Location, Resources are found, etc.).|

### Dungeon Crawling

Dungeons (as the concept of a closed-off adventure site) are the main sites that players will interact with during play.

### Wilderness Travel and Hex-ploration

#### Movement

_Original Idea from OSR Simulacrum : [Making Wilderness Play Meaningful - A System](http://osrsimulacrum.blogspot.com/2020/05/making-wilderness-play-meaningful-system.html)_

Traveling and Exploration are both means to go adventuring and adventuring by themselves. As the wilderness is a dangerous place (regardless of settings, this rules- and procedures-set assumes a "Points-Of-Light" milieu), movement in the wilderness should not be abstracted as "Ok, 5 days later, you arrive at [...]". Furthermore, the main difference between travel and exploration is simply the knowledge of the destination (you can travel TO somewhere specific, but you only explore the uncharted). Sites and Point of Interests discovered during Exploration may be afterwards used as destination for Travel, as long as players (and characters) remember where those have been discovered.

Actual movement, beyond the number of hex that the party can travel through per day, and position inside an hex are abstracted when playing in this context. Furthermore, the party is always considered in an hex, until they finalize their movement, then they are in the targeted hex.

Now, for the actual movement rules:

* The party has a number of travel point dependent on the milieu of travel.  __For land travel__, they have 4 points of travel per day.
* Moving into an hex is represented by 1 point of movement. In standard condition, the party may spent 1 point of travel to move into a new hex. This means that, by default, 1 point of travel is equivalent to 1 point of movement.
* The party composition and means of travel may allow 1 point of travel to represent more than 1 point of movement (i.e. Movement is easier, so the party travels further than usual), or may requires more than 1 point of travel to move into a new hex (i.e. Movement is harder, the party cannot travel as far as usual)
* Terrain and Weather may increase or decrease the cost of moving into a new hex (similar to the rules of party composition)
* The party cannot overspend travel point to move into an hex, but they may "start" movement with points remaining at the end of the day, which will then count for their first movement of the next day (e.g. Moving with 5 points of travel one day, then 3 the next is not allowed, but moving with 3 points one day, then moving with 3 and 2 points the next day is okay).
* The party cannot move more than twice the maximum amount of travel point they have, i.e. with 4 travel points, they cannot move more than 8 movement points.
* If moving into an hex would cost twice or more the maximum amount of travel point the party has, the hex is considered impassable and the party cannot enter it (unless they change their travel condition)

Here are also multipliers for the more common travel conditions. Note that those are multiplicative, e.g. if the party has a mount for everyone, but they are escorting a carriage, each travel point will allow them to move for `1 * 2 * 1/2 = 1` movement point, or 1 hex.

###### Table X: Land Travel Accommodation

| Accommodation                                                | Movement Multiplier |
| :----------------------------------------------------------- | :-----------------: |
| The party is traveling by foot                               |         x1          |
| All members of the party have a mount suitable for the terrain |         x2          |
| The party has a carriage                                     |        x1/2         |
| The party has more than 20 people                            |        x1/2         |
| The party has more than 50 people                            |        x1/2         |

###### Table X: Land Travel Environment

| Environment                          | Movement Multiplier |
| :----------------------------------- | :-----------------: |
| Traveling through plains             |         x1          |
| Traveling through hills              |        x2/3         |
| Traveling through marshes and swamps |        x1/2         |
| Traveling through forests and woods  |        x1/2         |
| Traveling through mountains          |        x1/4         |
| Traveling through high mountains     |   x0 (Impassable)   |
| There is a well maintained road      |         x2          |
| There is downtrodden road or a trail |        x1.5         |
| During rains                         |        x1/2         |
| During light snowfall                |        x1/2         |
| During heavy snowfall                |        x1/4         |

_**ToDo**: Define Travel points and Movement Multipliers for Water/Sea and Air travel._

#### Getting lost

_**ToDo**: Adapt "Getting Lost" rules from AD&D DMG_

#### Encounters

While travel or exploring, the Overloaded Encounter Die is used to simulate events outside the control of the players and characters. 

* While **traveling**, this encounter die is rolled after the party has spent half of its travel point, and during the night camp. 
* While **exploring**, this die is rolled after the party has spent its first travel point, after the party has spent all its travel point, and during the night camp. 

This table should be adapted to the current party condition, e.g. if the party is traveling through a desert, the _Free Turn_ may be swapped for _Waning Resources_ instead (to replicate the harshness of the environment), or if the party is in mostly civilized lands (around a city or a fortress), the _Free Turn_ can be a _Good Encounter_ instead, even during the night, instead of discovering a hidden site, there may be an encounter at the party camp.

###### Table X: Overloaded Encounter Die for Wilderness Movement

| Die Face | Event             | Precision                                                    |
| :------: | :---------------- | :----------------------------------------------------------- |
|    1     | Encounter         | The Referee rolls a random encounter appropriate for the current milieu. |
|    2     | Hidden Site       | The characters stumble upon a hidden site of the current hex. |
|    3     | Change of Weather | The referee determines a new weather applicable for the milieu. |
|    4     | Waning Resources  | The characters must rest and consume resources before venturing forth. They may either spend resources they have, or spend the next travel point foraging. |
|    5     | Free Turn         | Nothing specific happens, the characters can simply continue their journey unhindered. |
|    6     | Good Encounter    | The Referee rolls a good random encounter appropriate for the current milieu (Helpful NPC, Secured Location, Resources are found, etc.). |

#### Discovery

Features in an hex can have one of 3 visibility statuses: Overt, Hidden or Secret.

* __Overt features__ are visible and known by the characters immediately upon entering an hex, and some can even be used as landmarks (usually 1-in-6, as informed by the referee) for navigation to avoid getting lost. When used for navigation, such landmarks may be seen from 2 hexes afar, barring any terrain feature blocking the view (High Mountains, Deep Forests or Canopies, etc.).
* __Hidden features__ are only visible by the characters if they stumble upon them while traveling. They can be discovered randomly one at a time if the party spends 1 travel point searching through the hex, or they can be found specifically if the party knows what they are looking for and spends 2 travel points to look for it.
* __Secret Features__ may be hinted at by activity, signs found during encounters or at other sites of the hex or even rumors, but they can only be discovered if the party spends __all__ of its travel points at once searching through the hex. This search can only be started at the beginning of a travel day (when the party has not spent any travel point yet)