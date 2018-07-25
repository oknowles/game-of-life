# gameOfLife

A javascript implementation for [Conways Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life). 

## Usage
Include the `gameOfLife.js` file in your html and define a canvas with the id 'gameOfLife': 

```javascript
<script src="path/to/gameOfLife.js"></script>  
...
<canvas id='gameOfLife' height='500'></canvas>
```

A random simulation can be started by calling the static `GameOfLife.startGame()` method. A basic example can be found [here](https://oknowles.github.io/gameoflife.html).

## Optional Configuration Parameters
The `startGame` method takes the following optional parameters:
* **cellsHorizontal:** width of the grid *(default 200)*
* **drawColour:** hex colour of the live cells *(default #d7dde5)*
* **liveCellDensity:** portion of the cells that are alive at the beginning *(default 0.2)*
* **intervalMs:** the interval in milliseconds between each grid update *(default 150)*

For example, you can create a simulation with a grid of width 500, blue coloured live cells, 40% of cells initially alive and a 75ms interval between updates using:
```javascript
GameOfLife.startGame(500, '#83adef', 0.4, 75);
```
