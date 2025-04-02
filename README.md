# Game of Life

This project implements Conway's Game of Life, a cellular automaton simulation that demonstrates how simple rules can create complex patterns.

## Overview

Conway's Game of Life is a zero-player game that simulates the evolution of a grid of cells based on simple rules. Each cell can be either alive or dead, and its state in the next generation depends on its current state and the states of its eight neighbors.

### Rules
- Any live cell with fewer than 2 live neighbors dies (underpopulation)
- Any live cell with 2 or 3 live neighbors lives on to the next generation
- Any live cell with more than 3 live neighbors dies (overpopulation)
- Any dead cell with exactly 3 live neighbors becomes a live cell (reproduction)

## Project Structure

The project is implemented as a Jupyter notebook (`Copy_of_HW6_GameOfLife_rafael_hajjar.ipynb`) containing:
- Implementation of the Game of Life rules
- Visualization functions
- Testing utilities

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy (for array operations)
- Matplotlib (for visualization)

## Usage

1. Clone this repository
2. Open the Jupyter notebook `Copy_of_HW6_GameOfLife_rafael_hajjar.ipynb`
3. Run the cells in sequence to see the simulation in action

## Author

Rafael Hajjar
