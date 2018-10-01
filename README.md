RPS project
For this project from the Odin Project course, I had to write a Rock Paper Scissors game.
Writing a function for the selection of the computer wasn't too complex. I used the function Math.random*10 that choose a random interger. I got rid of the choice 0 so there was only 9 options which the same probability for each outcome.
For the function for one round of the game, the main issue was that the output was the right one for each situation (computer: Rock vs player: paper).
The last function is a bit more tricky. It's a function repeating 5 times the one round function. But the game function needs to use the returned value of str so declared a new variable that has the returned value and it worked.

DOMRPS project
For this project from the Odin Project course, I had to reuse Rock Paper Scissors game function I created a few weeks ago.
This time to win, you need to reach 
The point was to integrate a javascript script that would register the player selection via buttons and not anymore through a text input.
