# Rookh_Bot
A bot to play the Indian card game "Rookh"

Big picture goal: The bot/program will have the capability to play this game with a variety of strategies, chosen at startup.

Description: "Rookh" is a trick-taking Indian card game.

Game Rules:

The game starts with a standard 52-card deck. Multiple decks can also be used, if the number of players is too great. Ideally, post-distribution, each player should have at least 10 cards.

First, each player is given 5 cards. This is when bidding begins.

Bidding: Each player bids a number of points that they claim they will be able to earn, given their current cards. Bidding goes until a player bids a number no other player is willing to top, similar to auctions. Bidding are made in at least increments of 5 points. The highest bidder is chosen as the winner, and becomes the "Dealer". The Dealer then chooses the suit that will be the "Trump" suit for the game.

Next, the remaining cards are distributed among all players. Each player should have the same number of cards. If there are too few cards, then the excess cards are to be removed. Cards are removed starting from the lowest-number non-point cards, and moving upwards through the suits in the deck. Since the Trump cards have a special status, they are generally not removed. The Rookh also cannot be removed.

Once card distribution is complete, the Dealer chooses their partner. This partner is specified as someone possessing a specific card of the Dealer's choosing. Initially, the partner is unknown to all.


Point system:

The following cards have points corresponding to their numbers:
- 3 card
- 5 card
- 7 card
- 9 card
- 10 card

Special point cards:
- The "A" card has 15 points
- The "Rookh", or the 2 of spades, has a value of 20 points


Power system:

All cards have a "power". Essentially, they higher a card is in a suit, the more power it has.

Trump cards follow the same general rule, however, any and all Trump cards overpower, or "trump", all other cards (except the Rookh).

The Rookh is the highest card possible in the game.
When the Rookh is played, that trick/round becomes a guaranteed win.


Gameplay:

Objectives (How to win): The Dealer's objective is to hit their point target, which they bid earlier, and their partner(s) join them in this. Multiple partners can arise when multiple decks are used, due to there being multiple copies of cards in the new card pool.

The person who played the card with the highest power wins the trick, and collects all of the cards. At the end of the game, once the teams are revealed, usually by the hidden partner playing the card that identifies them as such, each team combines their cards and adds up their points.

If the Dealer's team hits their objective, they win. If not, the team of the people wins.
