# gameOfLife

A javascript implementation for [Conways Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life). 

## Usage
Include the `gameOfLife.js` file in your html and define a canvas with the id 'gameOfLife'. 

A game can be started by calling the static `GameOfLife.startGame()` method, which will randomly initialise the grid and start the game. A basic example can be found [here](https://github.com/oknowles/gameOfLife/blob/master/test.html).

## Optional Configuration Parameters
* **cellsHorizontal:** width of the grid *(default 200)*
* **drawColour:** hex colour of the live cells *(default #d7dde5)*
* **liveCellDensity:** portion of the cells that are alive at the beginning *(default 0.2)*
* **intervalMs:** the interval in milliseconds between each grid update *(default 150)*
