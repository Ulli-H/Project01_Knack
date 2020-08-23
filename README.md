# Project01_Knack
The first project is an interactive python version of the card game "Knack" (also known as "Schwimmen" or "Einunddreißig"). This is an approach to build a functioning game, with basic functionalities and as a sigle-player-game against the computer. 

The original card game "Knack" is made for two up to nine players. It's also known as "swimming"(German "Schwimmen") or "thirty-one"(French "Trente-et-un").

## The rules 

The game is played with a french card deck of 32 cards. (A second deck can be used if there are more than 6 players) It is played in direction of the clock, clockwise. Every player tries to achieve the highest combination of cards on his hand by swapping a card per round. The player with the lowest hand loses.

#### Goal

2 ways of collecting cards:
    - cards of the same suit
    - cards in the same rank 
    
##### Value of the cards:
- an Ace scores 11
- court cards (King, Queen and Jack) score 10 points each
- pip cards (10, 9, 8 and 7) score their respective values

The highest possible number of points is thirty-one. This i8s possible with:
1. an ace and two court cards (f.e. ace + king + queen)
2. an ace, a court card and a ten

The second highest hand can be achieved with 3 of the same rank and is scored with 30 1/2.
- three 7's, three kings, three nine's (of different suits, since there is only one of each suit)

#### Game flow

The dealer deals three cards, face down and individually, to each player. 

Afterwards he deals two packets of three cards to himself, face down as well. 

The dealer now takes a look at his first pack. If he decides to keep it he turns the second pack face up in the middle of the table. If he doesn't like it, he can switch with the second pack without looking and places his first pack in the middle of the table. The remaining cards are placed facedown in a stack on the side. 

The player on the left of the dealer starts. He can either swap one card of his hand with one from the middle or all three cards. Swapping 2 cards is not possible. 
If he doesn't want to change he can either shove for one round or close the game. To close the game he needs to have at least 20 points on his hand. 

To reduce the complexity of the game flow the computer/dealer only makes random choices. 

#### End of game 
A game ends in two ways:

- a player closes, says "I'll close", all the other players may swap or shove one more time. 
- a player holds 31 points on his hand and the game ends rightaway. Scores are taken as they are from the other players (This still needs to be implemented)

#### Scoring

Only pairs or prials of the same suit or for 3 of a kind are counted. 

(The scoring methods are still in progress)










