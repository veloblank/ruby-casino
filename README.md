Flatiron School Sinatra Project

This is not intended to be a robust casino application; only an 'unfair' roulette program. Casino roulette is 'unfair' because it does not pay out the appropriate winnings for the 'real' odds. For instance, hitting a number from 1 to 36 should be a payout $37 on a $1 bet when the number is hit. However, casinos pay out about $35, thus giving the house an edge. A player truly needs to be lucky in the long run to be a winner at roulette. Future modifications of this program could simulate the casino's winnings vs. a player's losses, but ultimately, on a long enough timeline, every player goes broke playing a system of 'unfair' roulette.

This application will have users, admins/moderators, and only one casino owner. Users can place bets and chat. Admins can chat, ban users, and moderate chat. Admins cannot place bets. Admins can view all users balances. The owner can chat. He can view the casino's winnings and all users balances. He cannot gamble or moderate chat.

This roulette system will use the European system, where there is only 1 green '0' on the wheel. Thus:

numbers 1 to 10 and 19 to 28, odd numbers are red and evens are black,
numbers 11 to 18 and 29 to 36, odd numbers are black and evens are red.
The number '0' is green.

The 'wheel' is numbered clockwise:
0-32-15-19-4-21-2-25-17-34-6-27-13-36-11-30-8-23-10-5-24-16-33-1-20-14-31-9-22-18-29-7-28-12-35-3-26

The bets taken are:

Payout
35 to 1:  straight - bet on single number

11 to 1:  street - bet on 3 consecutive numbers (7,8,9)
2 to 1:   column bet (a 12 number bet)
2 to 1:   snake bet (numbers 1, 5, 9, 12, 14, 16, 19, 23, 27, 30, 32, and 34)

1 to 1:   1 to 18 (low), or 19 to 36 (high)
1 to 1:   red or black
1 to 1:   even or odd

For the snake bet, a diagram may be needed for the user to understand the name of the bet, as the numbers are serpentine in their arrangement on a roulette table. This seems like it would be a fun bet to try to implement in the program. If a user can play more numbers at a time, roulette is more fun.

Commands for bets will begin with '!'. So, '!5 red' will be a bet of $5 on red. Special commands like '!all red' will be considered.

A reward system would be fun, where the user wins back some money from the casino based on the account creation time.
Otherwise, a '!500 deposit' command might need to be created.
