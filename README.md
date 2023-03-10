# Welcome to my Tic_Tac_Toe game:


My Tic tac toe game is a python based game which is ran through Code Insitute's mock terminal on Heroku.<br>

Users can play a one on one game of Tic tac toe against a computer A.I. On a board that consists of Nine squares number 1-9.<br>

- Here is a link to my live project https://tic-tac-toes.herokuapp.com/
- Here is a link to my Github repository
https://github.com/gareth-39/tic-tac-toe
<br><br>
![Alt text](readMe.images/LiveGame.png)<br><br>

# Libraries used:
-  Import sys:
- - Import sys provides various functions and variables that are used to manipulate different parts of the Python runtime environment.

- Import Random:
- -  import random module in Python defines a series of functions for generating or manipulating random integers.

- From time import sleep:
- - From time import sleep function is used to add delay in the execution of a program. We can use python sleep function to halt the execution of the program for given time in seconds.<br><br>


# How to play the game:

- The game displays a 3X3 grid
- The user(you) will start the game first with the letter 'X'
- The computer (opposition) will follow by the letter 'O'
- To place your letter type a number between 1-9 this will choose your position
- The first display their letter ('X', 'O')
  horizontally, vertically or diagonally wins!
- If all of the 9 spaces are full and no one has won,
  the game will end in a tie.
#

# Features:

- Enter your name letter only. 
- Press S to start.
- You pick a number then you opponent picks a number.
- First player to get Three in a row wins
- If you pick the same number as one already picked you will be told you have to pick another square.
- If there is no winner a tie will be comfirmed.

#
# Future Features:

- A shot timer.
- A scoreboard. <br><br>

# Testing:
- Re-tested numerous times as when I tested in the terminal it worked perfectly but did not work in Heroku realised when I fixed the game I needed to re-dploy my heroku link to implement the new code and changes.
- I sent my live link to family and friends so they could play the game.
- I ran it through my local terminal and the Code Institute Heroku terminal.
![Alt text](readMe.images/Game%20start.png)
![Alt text](readMe.images/name%20entry.png)
![Alt text](readMe.images/name%20entry.png)
![Alt text](readMe.images/finished%20game.png)<br><br>

# Bugs:
- I had a few indentation errors.
- I also had spelling errors.
- I had bug in my code when the user entered a number the game stopped working, it was a simple mistake in my print statement.
- I fixed these bugs by carefully reading over my work.
- My code had a serious error i never picked up on in testing when a letter was entered instead of a number the game crashed. The fix was i completely re-wrote the player input function which stopped the game crashing on Heroku. 

# Remaining bugs:
- There are no remaining bugs.

# Validator:
- PEP8
- - No errors were returned on https://pep8ci.herokuapp.com/ <br><br>
![Alt text](readMe.images/ci%20python.png)
<br><br>

# Deployment:
This project was deployment using Code institute's mock terminal on Heroku.

- Steps for deployment:
- - Sign up for heroku.
- - Create a Heroku app.
- - Set the buildpacks to Python and Nodejs in that order.
- - Add a confrig var (key) PORT (value) 8000.
- - Link the Heroku app to my repository.
- - Build the repository.
- - Click on deploy.
- - New page opens with working app.
<br><br>

# Credits:
- Code institute http://codeinstitute.net/
- Youtube https://www.youtube.com/
- Google http://google.com/
- Wikipedia Tic tac toe game http://wikipedia.com/
- Fellow colleagues on Slack.
- As always my mentor Jubril Akolade.