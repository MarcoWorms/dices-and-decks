# Dices & Decks

A tabletop rogue-like adventure to play alone with just dices and cards!

## Objective:

In Dices & Decks, your mission is to scale a treacherous tower teeming with menacing monsters, cunning traps, and valuable treasures. Successfully navigate each floor and conquer the boss at the summit to claim victory. However, if your hero's health is depleted to zero, the game ends. Triumphing over the game unlocks new challenges, allowing you to test your skills in increasingly difficult scenarios!

## Components:

1. RPG Dice Set (d4, d6, d8, d10, d12, d20).
2. Two complete decks of cards.
3. A sheet of paper to track your progress and character stats.

## Setup:

1. Remove Jokers from both decks and shuffle them together to form the game deck.
2. Draw 10 cards (floors) from the game deck and place them face-down to form the tower.
3. Create your hero by assigning the following stats:
    * Health: 30
    * Attack: 1d6
    * Defense: 1d4
    * Luck: 0

## Gameplay:

On each floor of the tower, you'll encounter one of four possible events: Monster, Trap, Treasure, or Empty Room. Reveal the first card in the row to determine the event type:

* 2-10: Monster (number = monster's health, d6 attack, d4 defense).
* J, Q: Trap (J = easy, Q = hard).
* K: Miniboss (monster with 10 health, d8 attack, d6 defense).
* A: Treasure.

### Monster:

1. Roll a d20 for initiative for you and one for the monster. If your roll is higher, you strike first; otherwise, the monster attacks first.
2. On your turn, roll your attack die (d6) and subtract the monster's defense (d4) to determine damage dealt. Reduce the monster's health accordingly.
3. On the monster's turn, roll the monster's attack (d6) and subtract your defense (d4) to determine damage dealt. Reduce your health accordingly.
4. Continue alternating turns until either you or the monster has 0 health. If your health reaches 0, the game ends. If the monster's health reaches 0, you may draw a card as a reward (see "Treasure" below).

*Attack and defense dices used in the above example are not accounting for player buffs or miniboss

### Trap:

1. Roll a d20 and add your luck modifier.
2. Compare the result to the trap's difficulty:
    - J (easy, 6+ to succeed)
    - Q (hard, 12+ to succeed)
- If you succeed, you disarm the trap.
- If you fail, you suffer damage according to the trap's difficulty:
    - J (1d4)
    - Q (1d6)
3. Then, draw a card as a reward (see "Treasure" below).

### Treasure:

Draw a card from the game deck and consult the following list for your reward:

* 2-5: Health Potion. Heal for the card's value + 2.
* 6-9: Gain a one-time-use weapon. Keep the card and discard it after adding the card's value to your attack roll.
* 10: Gain a luck point, increasing your luck modifier by 1.
* J: Improve your defense die by one level (1d4 -> 1d6 -> 1d8…).
* Q: Improve your attack die by one level (1d6 -> 1d8 -> 1d10…).
* K: Gain a special ability. Choose one now but use it whenever you want:
    * Double Die: Use once to double the value of any die.
    * Evade: Use once to avoid any damage.
    * Heal: Use once to restore 1d6 health.
    * Sneak: Use once to reroll your initiative roll, take the higher result.
    * Lucky Charm: Use once to add +5 luck when disarming traps.
    * Second Wind: Use once to regain 1d4 health when your hero dies.

* A: Draw two more treasure cards and choose one to keep.

Remember that when you draw a treasure card, you may choose to use the item immediately or save it for later, depending on your strategy and current situation in the game.

Dice Levels: 1d4 -> 1d6 -> 1d8 -> 1d10 -> 1d12 -> 1d20 -> 2d10 -> 2d12 -> 2d20

## Final Boss and Winning the game:

After beating the final floor in the tower, you have reached the boss room!

* Health: 20
* Attack: 1d10
* Defense: 1d6

If you defeat the Boss congratulations, you can proceed to the next Prestige level!

### Prestige:

After beating the game you have now leveled up your prestige to 1. This means you can start a new game with 1 Curse Card that will increase the difficulty of your game. The curse card is drawn in step 2 of setup after the tower is drawn.

Beating the game on prestige 1 unlocks prestige 2, beating 2 unlocks 3, and this can go on infinitely. Each prestige: 

- Adds 1 more curse card to be drawn on the start of a new game.
- Increase boss health by 10 times the prestige level, so in prestige 2 for example the boss has 20 extra health.
- Increase monsters initiative roll by 2 for each prestige level.

### Curse Cards:

* 2-5: Weakened Offense - Your attack die is reduced by one level (1d6 -> 1d4) for the entire game. (cannot reduce attack below 1d4.)
* 6-9: Weakened Defense - Your defense die is reduced by one level (1d4 -> no defense) for the entire game. (cannot reduce defense below 1d4.)
* 10: Unlucky - Your luck modifier is reduced by 1 for the entire game.
* J: Persistent Traps - Traps are more difficult to disarm. Increase the target number for disarming traps by 1. (Trap difficulty can’t get higher than 19.)
* Q: Mighty Monsters - Monsters gain an additional 1d4 health.
* K: Cursed Treasure - When you draw a treasure card, you must also draw a trap card and resolve it immediately.
* A: Tougher Monsters - Monster’s health increase by 2, boss health increase by 10.

If you draw multiple curses of the same type, their effects stack. For example, if you draw two "Weakened Offense" curses, your attack die is reduced by two levels (1d6 -> 1d4 -> no attack).
