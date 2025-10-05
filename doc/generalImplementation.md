# General Implementation

## client - server role
The idea is simple, client is not sure, basicly we can't trust any client due to the editabilitie of minecraft, so, if we want to insure a sense of fairness, we need to manage the client with the most precotion posible and give it the bare minimum of trust.

#### Role of the client
Beside of showing thing, the only thing client doses is to send input, for example, you don't "play a card", you just say "i use the card at the index 0 of my hand" and the server will handle it and play the card


#### Role of the server
Everything else, all the calculation, match management, card manipulation, etc... is handle by the server, we can afourd that due to the nature of the game, we are not making the new Overwatch, we make a TCG, a turn base game, witch by design, is fare less computionaly demanding.



# Data

## Card
TODO : Describe a card 
###### Compose of 
- {String} Identifier
- {uint} Cost
- {List<Tag>} Tags

## Tag
Tag are 