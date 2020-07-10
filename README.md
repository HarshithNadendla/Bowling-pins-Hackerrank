# Bowling-pins-Hackerrank
Bowling is a sport in which a player rolls a bowling ball towards a group of pins, the target being to knock down the pins at the end of a lane.

In this challenge, the rules of the game are slightly modified. Now, there are a given number of pins, and the pins are arranged in a horizontal line instead of a triangular formation. Two players have to play this game, taking alternate turns. Whoever knocks down the last pin(s) will be declared the winner.

You are playing this game with your friend, and both of you have become proficient at it. You can knock down any single pin, or any two adjacent pins at one throw of a bowling ball, however, these are the only moves that you can perform. Some moves have already been played. Suddenly, you realize that it is possible to determine whether this game can be won or not, assuming optimal play. And luckily it's your turn right now.

A configuration is represented by a string consisting of the letters X and I, where:

I represents a position containing a pin.
X represents a position where a pin has been knocked down.
An example of such a configuration is shown in the image below. Here, the number of pins is , and the  pin has already been knocked down.

Pins

Its representation will be IXIIIIIIIIIII.

Complete the function isWinning that takes the number of pins and the configuration of the pins as input, and return WIN or LOSE based on whether or not you will win.

Given the current configuration of the pins, if both of you play optimally, determine whether you will win this game or not.

Note

A player has to knock down at least one pin in his turn.
Both players play optimally.
Input Format

The first line contains an integer, , the number of test cases. Then  test cases follow.

For each test case, the first line contains a single integer , denoting the number of pins. The second line contains a string of  letters, where each letter is either I or X.

Constraints

Each letter of the string (representing the configuration) is either I or X.
There will be at least one I in the string.
