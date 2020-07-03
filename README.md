# Twenty One
##### *A game of Twenty One written in Ruby*

![beginning_image](https://i.imgur.com/44xjbt3.png)

### About:

This program is a Twenty One game written in Ruby and was built as part of the Launch School RB101 course. 

As part of the course, my role was to develop the following logic and add it to the game:

* Create the deck of cards containing the full 52 cards with the four suits.
* Shuffling the deck of cards.
* Dealing the player and dealer two cards each, while showing the player only the dealer's first card.
* Logic for the player hitting or staying:

![hit_or_stay_image](https://i.imgur.com/C1q09Pt.png)

* Once the player stays, the dealer's logic for hitting until reaching at least the score of 17 (which can be changed):

![dealer_logic](https://i.imgur.com/tCogTmU.png)

* Keeping score at the end of each round.
* The ability to have multiple rounds needed to win the game.
* Asking the player if they'd like to repeat the game after a winner is declared.


### Game Notes:

This version of Twenty One is written in Ruby and there is no front end. In order to play the game, you will need to download the file and run the Ruby program from the command line.

The game is designed for the player to always start off each round. At the end of each round one of three outcomes will occur: The player wins, the dealer wins, or there is a tie. The program will keep score and also a total number of rounds played, both shown in the terminal.

As a default, the first person to win 2 rounds wins the game. This number can be adjusted in the "TOTAL_ROUNDS" constant if you'd like to play less rounds or more rounds.

The game also is designed with the number 21 being the 'blackjack' number, but this can be adjusted if you'd like with the "BLACKJACK" constant.

When it's the dealer's turn to draw cards, after the player has selected to 'stay', the dealer will always continue to draw another card until the dealer reaches at least 17. This number can be adjusted with the "DEALER_HITS_UNTIL" constant.

At the end of the game, there is an option to play again which resets the scores.

![end_game_image]()

[The original code with full commit history can be viewed here](https://github.com/westonludeke/launch_school_rb101/blob/master/6_lesson/twenty_one.rb).