#Rock-Paper-Scissors-The-Game 




Rock, paper, scissors (also known as Rochambeau, Roshambo, or Janken)
Is a fun and easy game that anyone can learn and enjoy.
Things You Should Know
Rock beats scissors, scissors beat paper, and paper beats rock.
Agree ahead of time whether you’ll count off “rock, paper, scissors, shoot” or just “rock, paper, scissors.”
Use rock, paper, scissors to settle minor decisions or simply play to pass the time.

The game consists of two players making a choice between rock, paper, or scissors, and the winner is determined by the rules:

Rock beats Scissors
Scissors beats Paper
Paper beats Rock
The code first imports the random module to enable the computer to make a random choice between the options. It then prints the name of the game and creates a list of the options available.

The while loop will keep running as long as the user chooses to keep playing. Within the loop, the user is asked to input their choice, which is then converted to lowercase using the .lower() method. If the user's choice is not in the options list, the program will prompt the user to choose from the available options and continue the loop.

The computer then makes a random choice using the random.choice() method. The program then determines the winner based on the rules of the game using an if-else statement. If the user wins, the program will print a message indicating which option won. If the user loses, the program will print a message indicating which option won.

After each game, the user is prompted to play again. If the user inputs "yes", the loop continues. If the user inputs anything else, the loop will break, and the program will end with a message thanking the user for playing.
