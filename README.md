<h4> RPS project</h4> 
<p>For this project from the Odin Project course, I had to write a Rock Paper Scissors game.</p>
<p>Writing a function for the selection of the computer wasn't too complex. I used the function Math.random*10 that choose a random interger. I got rid of the choice 0 so there was only 9 options which the same probability for each outcome.
For the function for one round of the game, the main issue was that the output was the right one for each situation (computer: Rock vs player: paper).</p>
<p>The last function is a bit more tricky. It's a function repeating 5 times the one round function. But the game function needs to use the returned value of str so declared a new variable that has the returned value and it worked.</p>

<h4>DOMRPS project</h4> 
<p>For this project from the Odin Project course, I had to reuse Rock Paper Scissors game function I created a few weeks ago.
This time to win the game, you need to be the first to win 5 rounds by clicking on the button of your choice.
The main difficulty was to integrate a javascript script that would register the player selection via buttons and not anymore through a text input.</p>
