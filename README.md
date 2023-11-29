# Tic-Tac-Toe

Tic-Tac-Toe is a python terminal game. Tic-Tac-Toe is a two-player game. Each alternately marks their space with an O or an X in a nine square grid found in the game.


## How to play

Each alternately marks their space with an O or an X in a nine square grid found in the game.
And whichever player manages to mark three Xs or Os diagonally, horizontally, or vertically wins. Each player must also block their opponent while attempting to make their chain.


## Features

### Existing features

#### Player X get to Enter row and column number 

- The first player, in this case player X must enter row and column number to fix spot.

 ![Skärmavbild 2023-11-28 kl  12 19 56](https://github.com/matgus217/tic-tac-toe/assets/147818054/d72d6dd0-b8ab-4b9e-ac68-a3ce03348733)

#### Player X choose row: 1 and column number: 3. And the turn goes to player O.

![Skärmavbild 2023-11-28 kl  12 23 40](https://github.com/matgus217/tic-tac-toe/assets/147818054/fd997006-a563-4356-95b1-cc6b7a150edf)

#### Player O choose row: 1 and column number: 2. And the turn goes to player X again.

![Skärmavbild 2023-11-29 kl  07 09 40](https://github.com/matgus217/tic-tac-toe/assets/147818054/899dcc80-006f-40bc-819f-15045bba19c1)

#### Player X and O has make their moves.

![Skärmavbild 2023-11-29 kl  07 14 45](https://github.com/matgus217/tic-tac-toe/assets/147818054/82749431-b219-4372-9766-b192a71594e9)

#### Player X is the winner in the end and the game can begin again.

![Skärmavbild 2023-11-29 kl  07 13 38](https://github.com/matgus217/tic-tac-toe/assets/147818054/7a2211dc-14c6-49ad-975f-9982a9a65463)

## Data Model

#### As data model i used functions that stores everything that is needed to run the game such as
- Print methods that prints out what is happening in the game.
- A create_board variable this is where the game will take part.
- A get_random_first_player variable that will randomly choose a player to begin the game.
- A fix_spot variable that contains the players guess.
- A has_player_won variable that contains the winner of the game.

## Testing
- I have tested the code through a python validator and confirmed that there are no problems or errors.

![Skärmavbild 2023-11-29 kl  09 47 59](https://github.com/matgus217/tic-tac-toe/assets/147818054/6e9c653d-f24a-4a63-9924-23058ec7ee69)



   ## Bugs
  There are no bugs in the game

  ## Deployment

  #### The project was deployed using Code Institute's moch terminal for Heroku.

  #### Steps in deploying the project:
  - I cloned the repository
  - I created a new Heroku app
  - I set the buildpacks to Python and NodeJS
  - I linked the Heroku app to the repository
  - I clicked on Deploy


## Credits 
- I searched the internet for information and found a Python tutorial at [GeeksforGeeks](https://www.geeksforgeeks.org/python-programming-language/?ref=shm_outind)
- Code Institute for the deployment terminal
- I imported the random module to my project and read all about it at [python](https://docs.python.org/3/library/random.html)
