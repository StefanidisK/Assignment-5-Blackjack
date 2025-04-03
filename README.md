# Assignment 5: Blackjack
Create a Blackjack game for one player (The computer will be the dealer). The player will start at 100 points. For each round that the player wins, their score will increase by 10. For each round that the player loses, their score will decrease by 10. After each round, your game should ask the player if they want to play again (if they are not already broke!).

## Checklist
- [ ]Includes sufficient internal documentation (comments and header)
- [ ]Uses descriptive variable and function names
- [ ]Is organized with functions
- [ ]Has clear user prompts
- [ ]Labels output so that it is clear to the user what the output is
- [ ]Allows the user to continue playing until broke
- [ ]Adds 10 points for winning a round, deducts 10 points for losing
- [ ]Uses a full deck of cards
- [ ]Shuffles the deck
- [ ]Tells the user what their score is after each round
- [ ]Deals the player and dealer two cards
- [ ]Removes the cards from the deck (to prevent reusing cards)
- [ ]Shows only one of the dealer cards at the beginning of the round
- [ ]Shows the actual names of the card (ex. “King” not 13)
- [ ]Asks the player if they want to hit or stay
- [ ]Stops asking the player if they want to hit if they go bust
- [ ]Does not allow the player to stand if they have less than 15
- [ ]Shows the dealer’s hand
- [ ]Hits for the dealer until the dealer’s hand is 17 or more
- [ ]Calculates the values of the player and dealer hands correctly
- [ ]Counts each Ace as 11 unless this would cause the player to bust

  Win is calculated correctly:
- [ ]player < 21; player > dealer; player wins
- [ ]player < 21; player < dealer; dealer < 21; dealer wins
- [ ]player < 21; player < dealer, dealer > 21; player wins
- [ ]player < 21; player = dealer; dealer wins
- [ ]player > 21; dealer wins
- [ ]player = 21; player wins
