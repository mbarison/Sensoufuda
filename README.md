# Sensoufuda

A card-based battle game for 2 players, aged 10+

## Introduction

In the near future, the Axis of Evil and the Paladins of Hope will battle for the supremacy, the prestige and the dwindling resources of their dying planet. Guide a faction to victory against your opponent.

## Strategic Phase

TBD

Idea: RPS mechanism to define advantages & disadvantages.

## Tactic Battle

Once the enemies have chosen the place of their next encounter, the Tactic Battle begins.
The Tactic Battle is played with a deck of 48 cards divided into 12 "Theatre" suits. Each suit has its own colour and icon.
Most of the cards are plain cards, i.e. there is no extra symbol on them. There are also special cards:

- Strategists, indicated either by a ![star](icons/star.png) or ![star-half-stroke](icons/star-half-stroke.png) symbol.
- Heroes, indicated by one of these three symbols: ![award](icons/award.png), ![wrench](icons/wrench.png), ![biohazard](icons/biohazard.png).
- Resources, indicated  by this symbol: ![cubes](icons/cubes.png).

Here below is a summary table of all special cards in the deck:  

| Theatre      | Strategist                                          | Hero                                         | Resource                              |
|--------------|-----------------------------------------------------|----------------------------------------------|---------------------------------------|
| Air          | Air Marshal ![star](icons/star.png)                 | Ace ![award](icons/award.png)                |                                       |
| Land         | General ![star](icons/star.png)                     |                                              | Tank ![cubes](icons/cubes.png)        |
| Sea          | Admiral ![star](icons/star.png)                     |                                              | Battleship ![cubes](icons/cubes.png)  |
| Industry     |                                                     | Rosie ![wrench](icons/wrench.png)            | Factory ![cubes](icons/cubes.png)     |
| Propaganda   |                                                     | Influencer ![biohazard](icons/biohazard.png) | Newspaper ![cubes](icons/cubes.png)   |
| Intelligence | Spy ![star-half-stroke](icons/star-half-stroke.png) |                                              | Wiretap ![cubes](icons/cubes.png)     |
| Diplomacy    | Ambassador ![star](icons/star.png)                  |                                              | Treaty ![cubes](icons/cubes.png)      |
| Guerrilla    |                                                     | Partisan ![award](icons/award.png)           | Dynamite ![cubes](icons/cubes.png)    |
| Technology   |                                                     | Scientist ![wrench](icons/wrench.png)        | Death Ray ![cubes](icons/cubes.png)   |
| Space        |                                                     | Astronaut ![award](icons/award.png)          | Satellite ![cubes](icons/cubes.png)   |
| Atomic       |                                                     | Mutant ![biohazard](icons/biohazard.png)     | Nuke ![cubes](icons/cubes.png)        |
| Cyberspace   |                                                     | Hacker ![wrench](icons/wrench.png)           | Virus ![cubes](icons/cubes.png)       |

The 48 cards are shuffled and distributed as follows:

- 8 Cards to each player, to be kept in their hands. Players can look at their own cards.
- 8 Cards to each player, to be kept face down in the "Ally" deck. Players **cannot** look at their Ally deck cards, unless a special power allows them to do so.
- 8 Cards on the playing area between the players, face up.
- 8 Cards won't be distributed and will be kept face down, out of play. Players **cannot** look at these cards, unless a special power allows them to do so.

The 8 cards on the playing area are "Tactical Options" that each player can activate during the battle. To activate them, a player must play a card from their hand matching a Theatre suit available on the playing area.
Activated Tactical Options, and the cards used to activate them, are placed in front to each player to form a Tableau.
Tactical Options from the Tableau can be used to form combos that guarantee victory in the Tactical Battle and Victory Points.

### Game Turns

The Axis of Evil player starts the battle. They play a card from their hand, and then:

1. If there is no Tactical Option on the playing area with a matching Theatre suit, the card is added to the Tactical Options in the playing area.
2. If there are one or more Tactical Options with a matching Theatre suit on the table:
   1. If there is **only one** matching Tactical Option, the player must collect it.
   2. If there are **two** matching Tactical Options, the player chooses which one to collect, leaving the other one on the table.
   3. If there are **three** matching Tactical Options, the player collects them all.

Then, the player must flip the top card from the Ally deck and play it as if it were their own, following the same rules here above.
_Note: Collecting a Tactical Option is **mandatory** if the played card has a matching suit, either if played from the player's hand or from the Ally deck._

All played cards and collected Tactical Options are stored in a Tableau in front of the player. For convenience, I suggest the Tableau is arranged in four rows (or columns):

- Strategists
- Heroes
- Resources
- Plain cards

The player checks if any Combo is triggered. If so, then follow the instructions of the Battle Resolution Phase.
If not, play resumes with the next player.

### Combos

- Three Strategists (3 x ![star](icons/star.png)): 5 VP
- Three Strategists plus Spy (3 x ![star](icons/star.png) + ![star-half-stroke](icons/star-half-stroke.png)): 6 VP
- Four Strategists (4 x ![star](icons/star.png)): 8 VP
- Four Strategists plus Spy (4 x ![star](icons/star.png) + ![star-half-stroke](icons/star-half-stroke.png)): 10 VP
- Three Awards: Ace - Partisan - Astronaut (3 x ![award](icons/award.png)): 5 VP
- Three Wrenches: Rosie - Scientist - Hacker (3 x ![wrench](icons/wrench.png)): 5VP
- Five Heroes: Any five of ![award](icons/award.png)![wrench](icons/wrench.png)![biohazard](icons/biohazard.png): 1 VP, + 1 VP for each additional Hero
- Five Resources: (5 x ![cubes](icons/cubes.png)): 1 VP, + 1 VP for each additional Hero
- Four Atoms: (4 x ![atom](icons/atom.png)): 0 VP, and the battle ends immediately
- (Optional?) Troll Farms: Newspaper + Wiretap + Virus: 5 VP
- (Optional?) Blitzkrieg: Tank + Battleship + Dynamite: 5 VP

### Battle Resolution

The first player triggering a Combo is declared Victorious and has two choices:

1. **Declare Victory**: The player scores the VP granted by the Combo and ends the Battle. The game continue to the next Strategic Phase.
2. **Press On**: The player wants to continue the battle, trying to inflict a larger defeat to their opponent. The opponent in turn has the choice to:
   1. **Retreat**: the opponent concedes defeat, and retreats in good order. The victorious player scores the VP. The defeated, retreating player _keeps up to half of their unused hand cards for the next battle_. Fractions are rounded down. At the beginning of the next battle, the retreating player is dealt enough cards to fill their hand up to 8. The Ally deck is dealt as ususal. The game continue to the next Strategic Phase.
   2. **Counterattack**: the defeated player risks their strategic reserves to fight back and try to revert the result of the battle.

If the victorious player chooses **Press On** and the defeated player chooses **Counterattack**, the Battle resumes, starting with the defeated player.

The goal of the victorious player is either to create an addtional Combo or to improve an existing one. An example of an improved combo is the victorious player having 5 Resources and getting a 6th Resource to improve the Combo.
If the victorious player manages a successful **Press On**, the VP of all combos is added up and a 2x multiplier is applied.
The victorious player can now **Declare Victory** or try again to **Press On**, and the defeated player can still decide to either **Retreat** or **Counterattack**.
For each succesfull **Press On** the multiplier is increased by one: 2x, 3x, 4x. The fourth successful **Press On** action results in **Total Annihilation**: the defeated player's army is completely destroyed and the game ends immediately.

The goal of the defeated player to have a successful **Counterattack** is to create a Combo of their own. This Combo is successful even if its VP value is lower than the victorious player's Combo, and even if a multiplier is applied.
A successful **Counterattack** turns the tables! The defeated player becomes victorious and must now decide how to resolve the battle, while the victorious player is now on the back foot and is forced to defend themselves.

If during a **Press On/Counterattack** phase both players run out of cards in their hands and in their Ally deck without creating new Combos or improving existing ones, the battle is a **Stalemate**. All VP and special powers are discarded, new cards are dealt and a new Battle begins.
