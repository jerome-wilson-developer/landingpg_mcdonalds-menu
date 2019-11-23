frontend-nanodegree-arcade-game
===============================

Project-3 The Arcade Game Rubric for the GwG-Udacity Nanodegree Scholarship.
-----------------------------------------------------------------------------
Students should use this [rubric](https://review.udacity.com/#!/projects/2696458597/rubric) for self-checking their submission. Make sure the functions you write are **object-oriented** - either class functions (like Player and Enemy) or class prototype functions such as Enemy.prototype.checkCollisions, and that the keyword 'this' is used appropriately within your class and class prototype functions to refer to the object the function is called upon. Also be sure that the **readme.md** is updated with your instructions on both how to 1. Run and 2. Play your arcade game. 

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

The Technologies used to build this game.
--------------------------------------------
This game was built with semantic html5, pure css, and vanilla es6 javascript. No frameworks, libraries, or dependancies were used. Shout-outs to the great walkthrough videos that helped me from Ryan Boris, Lloan Alas, and Ryan Waite.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

How-to load and run this game.
----------------------------------------------
How-to run the game: The game is already loaded and ready to play. Use the up/down arrow keys to move waterGirl vertically from the top to the bottom of the world. Use the left/right keys to move waterGirl horizontally on the rows from left to right. You can also use the 'refresh arrow' at any time to refresh the game.
Click here to play this Classic Arcade Game in your browser: (https://drjwebsitedesign.github.io/P3_Classic-Arcade-Game/)

Click here to see a 3-min youtube video of the basic [Arcade Game](https://www.youtube.com/watch?v=dIu40myH9CY) uploaded by Esther Kim.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

The theme of my Arcade Game.
----------------------------------------------
waterGirl only has '5 Lives' to cross rocky roads, high grassy weeds, and make it home safely! waterGirl's loving aquatic family lives at the bottom of the world in the Pacific ocean. Her aquatic family can only survive on dry land for a short time. 

waterGirl is headed home from visiting her best friend at the top of the world in the Atlantic ocean. They both fear the gigantic landBugs that eat the waterPeople to survive! 

Can waterGirl return home without being eaten by the landBugs?? Can she safely cross the hard gravel roads and thick grassy weeds?? If she fails it will be ..... Rest in Peace for waterGirl!

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

How-to play the game and the Challenges for the Players against the landBugs.
-----------------------------------------------------------------------------
waterGirl loses a life 'each time' she collides with a landBug. She gets eaten up forever by the landBug if she collides with them 5 times. waterGirl Only has 5 lives to make it safely home from the top of the world(Atlantic Ocean) back to the bottom of the world(Pacific Ocean).  

However, if waterGirl makes it all the way to the Pacific Ocean without colliding with a landBug, then the player (You) wins the game. The player will receive 3 different messages to update your progress. The messages are: 1)You lose a life (and how many lives you have left to make it home), 2)you lose the game, or 3)you win!

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

Some Creative Changes i made to make the game more Challenging are:
----------------------------------------------------------------------
*Make The Game 95% Hands-Free!
The main creative focus driving my version of this game was to make it 95% hands-free for the players. That allows the players to focus 95% of their hand movements on using the 'arrow keys' to "safely navigate waterGirl", instead of deleting popUps, modals, 'X's, or buttons, etc. If the players have to constantly stop to remove 'event messages' displayed during the game, then the player has to mentally and emotionally re-focus their energy each time they move their hand from the 'arrow keys', over to the 'mouse', and then back over to the 'arrow keys'. 

This distraction has been eliminated by automating this game's four 'event messages' which are: a)the player loses a Life, b)the player loses the game after losing 5 lives, c)the player wins the game if waterGirl safely and successfully makes it home from the 'top of the world' to the 'bottom of the world' without being eaten by the 'landBugs', and finally lol, d)the 'rules of the game and the theme of the game' button. I used the 'setTimeout method' to automate the opening and closing of each 'event message' so that the players can keep their fingers positioned on the 'arrow keys' tne entire game. The automation also allows them to focus 100% of their energy ONLY on winning the game. 

*Create a Game Theme that makes the players compassionate waterGirl's safety!
    
*Created a different Scenery to make the game even more challenging than before! 

*Added a 4th landBug to evade to make it more difficult for waterGirl while returning home.

*Display a countdown of the number of lives waterGirl has left after being eaten by each landBug.

*waterGirl's journey is reversed. She travels from the top of the canvas to the bottom, instead of from the bottom to the top. Her 'y' coordinates are changed to make the code work.

*I re-arranged the rowImages to fit my 'game theme' and to create a more challenging trek across the roads, water, and grasslands. Re-arranged from 1-water, 3-stone, 2-grass ..... to 1-water(Atlantic Ocean), 2-stone(landBug turf), 2-grass(landBug turf), and 1-more water(Pacific Ocean).

*Reduced the canvas.height from 606 to 515 to help the canvas fit more squarely and centered on the body. The canvas would briefly overlap the page whenever the height of my display messages would render.
