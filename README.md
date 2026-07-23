# Set-Solver
The solver works with the game "Set" and has been adjusted to the online version "Triad Logic". 
You can use either the terminal version or the camera version. </br>
The terminal version works great, the downside is you need to enter the cards manually. With a little practice, you can enter the codes quick, but you'll never be as fast as the AI / if experts play the game. </br>
The camera version uses AI and it's accuracy depends on the trainings data. Since I didn't collect a lot of data, it doesn't work very well yet. It detects about half the cards right and some features of the other cards wrong. Hence I didn't add the .exe file for it. You can collect your own data (instructions below) or just use my model (which doesn't work yet).

## Terminal Version
Install the terminal.exe and run it. </br>
In the beginning you enter the 12 cards as codes. Each of the 81 cards have an individual code.
The program then suggests a set. Enter the new cards from left to right, top to bottom. 
If a set isn't possible, it asks for the 3 extra cards, just as in the game. 
The game stops after 81 cards have been decked, so a full game. 

Example code help: </br>
Values: 1 2 3

Count: 1 2 3 </br>
Colour: red green blue </br>
Pattern: empty striped filled </br>
Shape: Round Curved Diamond </br>

Examples: </br>
1 green filled Diamond: 1233 </br>
2 red filled Curved: 2132

## Camera Version
It is best to have a webcam connected to the laptop that records the phone screen. On the window that pops up, only your phone must be visible. Position it such that the cards fall neatly within the 3x5 grid. 
The program tries to auto detect the card code and runs a similar code as above. 
If it finds a set, it prints it. 

TODO (not required, but very useful): 
- I still need to change the output, to make it display the set on the live feed. 
- It auto-detects how many cards are on the screen.

# Use of AI
I used ChatGPT much more than in my other projects as I don't have a lot of experience with Computer Vision and AI. I asked for ideas on how to detect the different features. I tried out what I found best. But many things didn't go as planned, so I did use a some AI-generated code. But I usually still had to adjust it and most of the code is self-written. 
