# Functions

## Functions
https://www.w3schools.com/js/js_functions.asp

## Game clock
A game clock is the function call that tells the game to update. For example, if we want snake to run at 5 frames per second we will need something to tell the game to update once every 200 milliseconds. This can be achived in JS with `setTimeout(function, milliseconds)` This will call a function after a certerine number of milliseconds. If we put it in the function that it calls than we will get a loop that happens every set number of milliseconds. There is an example below. You will also have to call the function that containes setTimeout at least once to start it. 

https://www.w3schools.com/jsref/met_win_settimeout.asp

https://www.w3schools.com/js/tryit.asp?filename=tryjs_timing_clock

## Canvas Update
Now that we are starting to make stuff change on the canvas we need to clear before drawing on it again. To clear the canvas just call `ctx.clearRect(0, 0, 800, 800);`

## Task
1) Create a rectangle that moves across the screen.

2) Instead of setting a color with a word you can use rgb values. Make it change color too. For example:

`ctx.fillStyle = "rgb(255,165,0)"` <br>
 
Bonus: If you are really keen get it to bounce off a wall. 