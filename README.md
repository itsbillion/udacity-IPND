# udacity-IPND
These are the necessary prompts when creating the game
1. Create a starter Player class always plays 'rock'.
2. Update the Game class so that it displays the outcome of each round, and keeps score for both players. You can use the provided beats function, which tells whether one move beats another one
3. Create a HumanPlayer subclass, whose move method asks the human user what move to make.

At the end of each game round, the Game class calls the learn method on each player object, to tell that player what the other player's move was. This means you can have computer players that change their moves depending on what has happened earlier in the game.
To do this, you will need to implement learn methods that save information into instance variables.
4. Create a ReflectPlayer class that remembers what move the opponent played last round, and plays that move this round. (In other words, if you play 'paper' on the first round, a ReflectPlayer will play 'paper' on the second round.)
5. Create a CyclePlayer class that remembers what move it played last round, and cycles through the different moves.
6. Create a Random Player class that can choose from the moves at random.
