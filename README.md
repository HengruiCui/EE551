
# EE551
## Five in a row
### Introduction
Five in a Row is an abstract strategy board game and is also called Gomoku, Gobang. It is traditionally played with go pieces (black and white stones) on a go board. However, once placed, pieces are not moved or removed from the board.<BR/>
<BR/>
### Rules
Black plays first, and players alternate in placing a stone of their color on an empty intersection. The winner is the first player to get an unbroken row of five stones horizontally, vertically, or diagonally.<BR/>
<BR/>
### package
Use graphics package and getMouse function to realize the function of the game. I use graphics to make a cheeseboard like this:
![example](https://github.com/HengruiCui/EE551/blob/master/cheese.png)<BR/>
Then I make a algorithm to complete the game.<BR/>
<BR/>
### Result
#### Player win
I try to win the game. Putting 5 black pieces in a row, so that we can see the results like this.
![player win](https://github.com/HengruiCui/EE551/blob/master/player%20win.png)
#### AI win
When I let AI win. It puts 5 white pieces in a row, so that we can see the results like this.
![AI win](https://github.com/HengruiCui/EE551/blob/master/AI%20win.png)
### Conclusion
This AI do not have ability to study so it cannot be stronger and stronger after several games. Because I just set the strategy that prevent players from winning first and then try to win the game in the code. So its most important duty is to defense rather than attacking.
