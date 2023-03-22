# Rogue Ascension

> A tabletop roguelike adventure you can play with common cards and dices!

<img width="500" src="https://user-images.githubusercontent.com/7863230/226544593-fc280ebd-04b7-40b9-a98d-6f51eab45872.png" />

## Objective

Your mission is to scale a treacherous tower teeming with menacing monsters, cunning traps, and valuable treasures. Successfully navigate each floor and conquer the boss at the summit to claim victory. However, if your hero's health is depleted to zero, the game ends. Triumphing over the game unlocks new challenges, allowing you to test your skills in increasingly difficult scenarios!

## Components

- 2 decks of cards (or use https://deck.of.cards/).
- 1 set of D&D dices (or use https://diceroll.fun/).
- A sheet of paper to track your progress and character stats.

## Setup

1. Remove Jokers from both decks and shuffle them together to form the game deck.
2. Draw 10 cards (floors) from the game deck and place them face-down to form the tower.
3. Create your hero by assigning the following stats:
    * Health: 30
    * Attack: 1d6
    * Defense: 1d4
    * Luck: 0

## Gameplay

On each floor of the tower, you'll encounter one of four possible events: Monster, Trap, Treasure, or Miniboss. Reveal the first card in the row to determine the event type:

* 2-10: Monster (number = monster's health, d6 attack, d4 defense).
* J, Q: Trap (J = easy, Q = hard).
* K: Miniboss (monster with 10 health, d8 attack, d6 defense).
* A: Treasure.

### Monster

1. Roll a d20 for initiative for you and one for the monster. If your roll is higher, you strike first; otherwise, the monster attacks first.
2. On your turn, roll your attack die (d6) and subtract the monster's defense (d4) to determine damage dealt. Reduce the monster's health accordingly.
3. On the monster's turn, roll the monster's attack (d6) and subtract your defense (d4) to determine damage dealt. Reduce your health accordingly.
4. Continue alternating turns until either you or the monster has 0 health. If your health reaches 0, the game ends. If the monster's health reaches 0, you may draw a card as a reward (see "Treasure" below).

*Attack and defense dices used in the above example are not accounting for player buffs or miniboss

### Trap

1. Roll a d20 and add your luck modifier.
2. Compare the result to the trap's difficulty:
    - J (easy, 6+ to succeed)
    - Q (hard, 12+ to succeed)
- If you succeed, you disarm the trap.
- If you fail, you suffer damage according to the trap's difficulty:
    - J (1d4)
    - Q (1d6)
3. Then, draw a card as a reward (see "Treasure" below).

### Treasure

Draw a card from the game deck and consult the following list for your reward:

* 2-5: Health Potion. Heal for the card's value + 2.
* 6-9: Gain a one-time-use weapon. Keep the card and discard it after adding the card's value to your attack roll.
* 10: Gain a luck point, increasing your luck modifier by 1.
* J: Improve your defense die by one level. d4 -> d6 -> d8…
* Q: Improve your attack die by one level. d6 -> d8 -> d10…
* K: Gain a special ability. Choose one now, but you can use it on any turn of yours:
    * Double Die: Use once to double the value of any die.
    * Evade: Use once to avoid any damage.
    * Heal: Use once to restore 1d6 health.
    * Sneak: Use once to reroll your initiative roll, take the higher result.
    * Lucky Charm: Use once to add +5 luck when disarming traps.
    * Second Wind: Use once to regain 1d4 health when your hero dies.
* A: Draw two more treasure cards and choose one to keep.

Remember that when you draw a treasure card, you may choose to use it immediately or save it for later, depending on your strategy and current situation in the game.

Dice Levels: d4 -> d6 -> d8 -> d10 -> d12 -> 2d8 -> d20 -> 2d10 -> 2d12 -> 3d10 -> 2d20

## Final Boss and Winning the game

After beating the final floor in the tower, you have reached the boss room!

* Health: 20
* Attack: 1d10
* Defense: 1d6

If you defeat the Boss congratulations, you can proceed to the next Ascesion level!

### Ascesion

After beating the game you have now leveled up your ascesion to 1. This means you can start a new game with 1 Curse Card that will increase the difficulty of your game. The curse card is drawn in step 2 of setup after the tower is drawn.

Beating the game on ascesion 1 unlocks ascesion 2, beating 2 unlocks 3, and this can go on infinitely. Each ascesion: 

- Adds 1 more curse card to be drawn on the start of a new game.
- Increase boss health by 10 times the ascesion level, so in ascesion 2 for example the boss has 20 extra health.
- Increase monsters initiative roll by 2 for each ascesion level.

### Curse Cards

* 2-5: Weakened Offense - Your attack die is reduced by one level (1d6 -> 1d4) for the entire game. (cannot reduce attack below 1d4.)
* 6-9: Weakened Defense - Your defense die is reduced by one level (1d4 -> no defense) for the entire game. (cannot reduce defense below 1d4.)
* 10: Unlucky - Your luck modifier is reduced by 1 for the entire game.
* J: Persistent Traps - Traps are more difficult to disarm. Increase the target number for disarming traps by 1. (Trap difficulty can’t get higher than 19.)
* Q: Mighty Monsters - Monsters gain an additional 1d4 health.
* K: Cursed Treasure - When you draw a treasure card, you must also draw a trap card and resolve it immediately.
* A: Tougher Monsters - Monster’s health increase by 2, boss health increase by 10.

If you draw multiple curses of the same type, their effects stack. For example, if you draw two "Weakened Offense" curses, your attack die is reduced by two levels (1d6 -> 1d4 -> no attack).

# Multiplayer: Co-op Up to 4 players

By appliying the following adjustments to the game's rules you can play together with up to 4 players:

## Multiplayer Setup

- Each player creates their hero and use the same ascesion level as other players.
- Determine the turn order by rolling a d20 for each player. The highest roll goes first, followed by the next highest, and so on.
- Add 5 additional cards (floors) to the tower for each additional player.
- Increase monsters' initiative rolls by 1 for each additional player.

## Multiplayer Gameplay

- If one player dies, the game is over!!

On each floor, follow these steps:

- The active player reveals the first card in the row and resolves the event as described in the original rules.
- If the event is a Monster or Miniboss, all players participate in the combat, taking turns according to the predetermined turn order. The monster attacks each player in order, and each player has the opportunity to attack the monster on their turn.
- If the event is a Trap, the active player attempts to disarm it. Other players may assist by spending a luck point, which grants the active player a +1 bonus to their roll.
- If the event is a Treasure, the active player draws the treasure card and decides whether to use it or save it for later. If they save it, the treasure card is added to their inventory. You can use your treasure and ability cards on other players, but only in your turn.
- When the active player's turn is over, the next player in turn order becomes the active player, revealing the next card in the row and resolving the event.

## Multiplayer Final Boss

- Increase boss health by 20 per aditional player. (so 1 player 20 helath, 2 players 40 health, etc)
- Ascesion boss health bonus is also multipied by amount of players (so 2 players playing in ascesion 2 adds 40 extra health to boss)
- All players participate in the boss fight, taking turns according to the predetermined turn order.
- The boss attacks each player in order, and each player has the opportunity to attack the boss on their turn.
- Players can use their special abilities and items to support each other during the boss fight.

## Multiplayer Ascesions

- For each ascesion level, increase the boss health by 10 times the number of players (e.g., in ascesion 2, the boss has 40 extra health per player).
- Each player draws one Curse Card per ascesion level at the start of a new game. Curses applies only to this player

This multiplayer mode maintains the game's challenge while allowing players to strategize and cooperate. Players can support each other by using their abilities and items, making the game more engaging and enjoyable for all.
