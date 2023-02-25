# PLAYING-UNO-GAME

1) First, we import the random module to shuffle the deck of cards.
2) We define the cards that make up the deck of Uno cards. There are four colors: Red, Yellow, Green, and Blue. There are numbers from 0 to 9 for each color, as well as special cards like Skip, Reverse, and Draw Two. Additionally, there are two wild cards: Wild and Wild Draw Four. We create a list of all the possible cards in the deck.
3) We shuffle the deck using the shuffle function from the random module.
4) We ask the user to input the number of players, and then prompt each player to enter their name. We store the players as a list of dictionaries, where each dictionary has a "name" key and a "hand" key. The "hand" key contains a list of the cards in that player's hand.
5) We deal seven cards to each player by popping them from the top of the deck and appending them to the player's hand.
6) We set up the discard pile by popping a card from the top of the deck and appending it to the discard pile.
7) We set up the game loop. The direction variable is used to determine whether the game is currently going clockwise (1) or counterclockwise (-1). The current_player variable keeps track of whose turn it is. The playing variable is used to determine whether the game is still being played.
8) In each iteration of the game loop, we print out the current state of the game. This includes the top card of the discard pile, the direction of the game, and the number of cards in each player's hand.
