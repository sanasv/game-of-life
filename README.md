
# Conway's Game of Life (Java)

This repository contains a Java implementation of **Conway's Game of Life**, a cellular automaton devised by mathematician John Horton Conway. The simulation evolves based on a set of simple rules applied to a grid of cells, producing surprisingly complex behavior.

## 🔗 How to Run

1. Download the `GameOfLife.jar` file from the repository or releases.
2. Move the file to your Desktop (or any preferred location).
3. Open **Terminal** and run the following commands:

```bash
cd ~/Desktop
java -jar "GameOfLife.jar"

> 💡 Make sure you have Java installed (Java 8 or later).

The application will launch a GUI window where you can visualize the evolution of the grid based on the Game of Life rules.

---

## 📦 Features

* Customizable grid size
* Play/Pause/Step controls
* Random initial state generation
* Choice of shapes
* Clear and reset grid
* Help menu with game description and how to play
* Simple and clean UI

---

## 📚 About Conway's Game of Life

The Game of Life is a zero-player game, meaning its evolution is determined by its initial state, with no further input. Each cell interacts with its eight neighbors and follows these rules:

1. Any live cell with two or three live neighbors survives.
2. Any dead cell with exactly three live neighbors becomes a live cell.
3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.



