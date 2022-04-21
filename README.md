# MASTERMIND #
Based on the original physical boardgame, this digital version challenges a player to solve a secret code of four colors within ten moves. 

## Technologies Used ##
_Languages:_ CSS, HTML, Javascript\
_Libraries:_ ReactJS\
_API:_ Random.org API for code generation

## Setup ##
1. Clone the repository code with ```git clone https://github.com/TheIanCannon/mastermind-react.git```.
2. Install node modules with ```npm install```.
3. Run the app with ```npm start``` and browse to Localhost:3000.

## Get Started ##
1. The objective is to match the hidden code of four colors at top.
2. Click on any of the eight colored dots to select one and add it to the blank rows, starting with the lowest first.
3. Click ```✗``` to reset the current row at any time.
4. Click ```✓``` to submit the attempted solution. A solution is accepted only if all four spaces have been filled.
5. Upon submission, light grey (wrong color), dark grey (right color/wrong location), and black (right color/location) pips randomly fill each of the four hint spots next to the current row.
6. The player wins if the solution is correct. Otherwise, the next blank row becomes active. The player loses the game if they are unable to solve in ten rounds.
7. Click ```Reset``` to restart the game at any time.