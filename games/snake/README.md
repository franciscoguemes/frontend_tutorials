22.02.2019  --> Coded while I am flying to Madrid :-)


This site is an example site taken from the video: https://www.youtube.com/watch?v=UJvL4i6UPbY



The site might not be 100% like in the video example, it contains some 
improvements such as:

+ Ignores the same key pressed several times
+ Ignores the opposite direction. I.e. If the snake goes down it ignores
	the up key pressed since the snake can not go backwards.

/***********************************************************************************/

Future improvements:
+ Scoring
+ Game over (letters)
+ Add a mode where hitting the walls also kill the snake
+ Add another item that kills the snake
+ Improve the graphics with images (like an apple).
+ Choose levels of difficulty
	+ Super Easy (Slow and walls do not kill)
	+ Easy (Slow)
	+ Difficult (Fast)
	+ Super difficult (Fast and walls kill)
	+ Dead mode (Fast, walls kill and double of bombs)

/***********************************************************************************/

To get autorefresh, at the project directory execute:
	browser-sync start --server --files *.html *.css
