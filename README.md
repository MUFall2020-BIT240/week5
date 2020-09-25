# week5
Building an interactive, HTML/JS based game!

IN-CLASS GROUP WORK
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
- Create a "<p>" for the players name and hp
- Create a "<p>" for the current_enemies name and hp
- Using javascript DOM, update the .innerText of those elements
- At the end of the "skirmish" function, update the hp on 
	the screen for both player and monster
