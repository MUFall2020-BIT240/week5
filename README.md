# week5
Building an interactive, HTML/JS based game!

## IN-CLASS GROUP WORK
We want to utilize the DOM and make the game more interactive
- Create a "current_enemy" key in the game object
- Populate that key with a random monster from your array (like we did above)
- Add a button on the screen called "Attack" (give it an ID as well)
- When that button is pressed (eventlistener), call a function named 
		"skirmish"
- The skirmish function is going to subtrack our user's damage from 
	the current enemy's hp
- AND take the current_enemies attack from our HP
- After doing both of those things, check to see if either our or the 
	monsters HP is <= 0
- If it is, use alert() to end the game

We also want to display data about the game on the screen so
	my ma' can play without using the console
- Create a paragraph tag for the players name and hp
- Create a paragraph for the current_enemies name and hp
- Using javascript DOM, update the .innerText of those elements
- At the end of the "skirmish" function, update the hp on 
	the screen for both player and monster

## Homework

- Add a value to your user object called "has_potion" and set the value to true
- Add another button to the screen for 'drink potion'
- When that button is clicked, call a function called 'drink potion'
- In the function, set the "has_potion" key to false
- Also, add 10hp to your user's current HP
- If the game.user.has_potion is false, use an alert to let the user know that they don't have a potion to use.
