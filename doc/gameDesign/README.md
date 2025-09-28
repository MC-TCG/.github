# Game Design Documentation
## Content Table
- [Game Design Documentation](#game-design-documentation)
  - [Content Table](#content-table)
  - [Introduction](#introduction)
    - [In a few words](#in-a-few-words)
    - [Design reference and inspiration](#design-reference-and-inspiration)
  - [Game mechanic](#game-mechanic)
    - [Main mechanic](#main-mechanic)
        - [Card crafting mechanic](#card-crafting-mechanic)
        - [punch mechanic](#punch-mechanic)
    - [Board](#board)
    - [Player resource](#player-resource)
    - [Type of card](#type-of-card)
    - [Entity](#entity)
    - [Deck composition](#deck-composition)
    - [TCG game steps](#tcg-game-steps)
  - [Game loop](#game-loop)
    - [General game loop](#general-game-loop)
    - [Progression loop](#progression-loop)
    - [Card master (if we have the time)](#card-master-if-we-have-the-time)
    - [Card design](#card-design)

## Introduction
### In a few words
Basically it's heartstone in minecraft without the greedy aspect of it. Gain cards by playing your world, create the most powerful and destroyed your opponent directly in minecraft to become "The coolest card player" in your server. Don't have access to a computer ? Never stop grinding with a web client, with that you can enjoy your minecraft in their fullest

### Design reference and inspiration
This mod takes inspiration from Heartstone, Slay the spirit, Wild frost and ofc Minecraft

## Game mechanic
### Main mechanic
So, it's a energy-based card game, each turn you have 3 energy to spend. To use card, or do certain action you will need those energy, for exemple to use the attack card you will need 2 energy (indicated by the card). Your deck is composed of 20 cards. At the start of the game, each player draw 5 cards, you redraw cards by spending 3 energy but the cost of doing a redraw lower each turn and will be reset to 3 when redraw. When you use a card, this card is not "destroyed", it go to the discard pile and when you redraw, this discard pile will rejoin your deck. To resume, when you redraw you CAN'T get any of your initial hand card, they would be available next redraw

##### Card crafting mechanic
In this game, you can craft card, to be more accurate, you can combine and transform card in to new card.
Example : You will not start your game with a sword in your deck, to get one you will first need to get 2 card from your deck, a stick and a material (for this example, let say a diamond), when you get those 2 in your hand, you can select them and use 2 energy to craft them, which will result into a fresh new card, a sword (to be exact, you will be able to choose between all other card requiring a stick and a diamond, this mechanic make a your deck more versatile while preserving a balance on top of balancing powerful card, for exemple a netherite sword). When you craft your diamond sword, the diamond and the stick are destroyed (for real, those 2 cards are gone from your deck for the game) and the sword will be in your hand :]

##### punch mechanic
For 1 energy, you can punch something, no card require, you can just punch (and due to the 1 energy cost, you can do it 3 time by turn).
punch do 1 damage or 1 block damage

### Board
Each player have 3 spot to place what ever entity they want
### Player resource
- Health : Each player have 20 health (to match minecraft)
- Energy : 3 per player and per round, it can be increase but only with certain set-up or card
- 
### Type of card
there is 4 main type of card
- Placable card, typically a block or a mob
- Tool card, example a sword or a pickaxe
- Action card, your classic spell for any tcg
- Resource card, they are special card use exclusively to craft, typically a diamond
### Entity
Entity can be of 2 main type, Mob and Block
there severals differences between them but the main one is there health value. In this game there is 2 type of health, health and block health {TODO:change the name} and health can only be damage by classic damage and block health by block damage, naturally, certain card will do certain type of damage and not the other, other will do both.

### Deck composition
like said above, a deck is composed of 20 card, but it's not the full story, you can only get 2 example of a card in your deck, so be creative
### TCG game steps
At start a random player is set to play first, they will start with 2 energy and they can not use punch. The second player to play can as no restriction

## Game loop
### General game loop
The idea is to link this TCG to your classic minecraft. So the basic game loop is : play minecraft -> do a specific achievement (example : obtaining a obsidian block) -> getting the achivement will unlock the card for your account, allowing you to use it in a deck

TODO : found a way to motivate player to play the game except for beating there friend
Idea : 
- ladder and ranking of all player in the server
- battle coins, can be use to unlock specific card by trading them with a special villager
- obtaining a way to get shiny card (will change nothing to the card beside the fact they are cooler)
- idk, need to found something
### Progression loop
TODO

### Card master (if we have the time)
Card master are special kind of villager found in village or in specific structure, they can be challenge by the player in order to progress in the mode. The goal in single player is to fight "THE CARD GOD" (idk, the guys who's really master MC-TCG) which is a special card master found in hes temple, in order to get to the temple, the player is needed to have defeat 3 TCG boss (other villager in there struct). They can be found by fighting card master at village, once defeated they will give you a map to the structure.

Beside that, Card master can trade with you special card for coins you will only be able to get by winning the MC-TCG

btw it would be so cool to be able to fight any villager and depending of the profession, there deck will change
and depending of what level of master the villager is, there deck became more and more efficient and naturaly more difficult to beat for the player

### Card design
TODO