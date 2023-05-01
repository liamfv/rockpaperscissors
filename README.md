# rockpaperscissors
The Odin Project's Rock, Paper, Scissors exercise project

This exercise required me to ask the user for an input through the prompt function.
The input had to be rock paper or scissors. It also required me to make it case insensitive, so I had to use the .toUpperCase() function. 
It was not required to validate input but I felt it necessary, so I added input validation to the user's choice. 
After gathering the user's input, we had to generate a computer's choice of Rock Paper or Scissors in a getComputerChoice() function. To do this, I used the Math.floor and Math.random functions to generate a number between 1-3. I then associated each number with a possibility: 1 for Rock, 2 for Paper, and 3 for Scissors, and returned it. 
After having both the user and the computer's choices, I simulated one round of gameplay through the playRound() function which would compare both choices and through conditionals decide if the player won, lost, or tied. It used to be more specific with its return values (i.e., would return a "You lose! Paper beats Rock!" string), but it had to be adjusted later on for the game() function.
The game() function would be used to simulate 5 rounds of Rock, Paper, Scissors. When the function is called, it creates a variable to keep track of the player score and a variable for the computer's score, and a result variable to store the return value of playRound() each time it was called. 
Then, game() would iterate 5 times over the playRound() function, logging each victory, loss, or tie and updating the player and computer's scores if necessary. 
After the loop is over, the scores of the player and computer are compared through conditionals in order to declare a winner. 

This was a fun project to do as it helped me recall some of my problem-solving skills from school in a different manner. I enjoyed applying functions I learned about through the JavaScript Fundamentals lessons and I can't wait to revisit this code in the future to improve it. 