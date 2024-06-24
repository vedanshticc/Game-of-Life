# Conway's Game of Life Web App

## Table of Contents
* [About Game of Life](#about-game-of-life)
* [Rules of the Game](#rules-of-the-game)
* [Key Features](#key-features)
* [Tech Stack Used](#tech-stack-used)
* [Installation](#installation)
* [Some Famous Patterns](#some-famous-patterns)


## About Game of Life
Welcome to the Conway's Game of Life Web App! This React-based interactive application allows you to explore the fascinating world of cellular automata through John Conway's famous Game of Life. Create intricate patterns, watch them evolve, and enjoy the mesmerizing dynamics that emerge.

## Rules of the Game
At every generation / timestamp:
- A live cell dies if it has fewer than two live neighbors.
- A live cell with two or three live neighbors lives on to the next generation.
- A live cell with more than three live neighbors dies.
- A dead cell will be brought back to live if it has exactly three live neighbors.

The simulation continues onward to the next generation until a stable layout is achieved.

## Key Features
### Interactive Simulation
The user can create custom starting layouts and observe their evolution through time.

### Custom Update Interval
The user can control the speed of the simulation by adjusting the update interval time. Speed it up for a dynamic display or slow it down to observe each generation closely.

### Start/Stop the Simulation Anytime
The user has the power to start and stop the simulation at any stage, allowing him to closely examine specific generations or patterns.

### Clear All Cells
Reset the grid to its initial state, where all cells are dead. This feature is particularly useful when you want to start fresh or experiment with new patterns.

### Random Starting Layout
Generate a random starting layout of living cells to kickstart the simulation. This feature is perfect for exploring the diverse possibilities and patterns that can arise in the Game of Life.
 

## Tech Stack Used
- HTML
- CSS
- JavaScript
- React.js

## Installation

- Clone the repository by opening your terminal and navigating to the directory where you want to clone the repository. Then, run the following command:
```bash
  git clone https://github.com/t-kadre/Game-of-Life
```

- Navigate to the App Directory:
```bash
  cd Game-of-Life
```

- Install the required dependencies using npm package manager:
```bash
  npm install
```
- Start the development server:
```bash
  npm start
```
- Access the App by visiting 'http://localhost:3000' 


## Some Famous Patterns

- Glider Gun: a pattern with a main part that repeats periodically and that also periodically emits gliders


https://github.com/t-kadre/Game-of-Life/assets/106656556/643e8e1a-d912-4ec8-bf65-e9efb626d5fc




- Reflector: a stable or oscillating pattern that can reflect some specific type of spaceship (usually a glider) without suffering permanent damage



https://github.com/t-kadre/Game-of-Life/assets/106656556/81547b09-98f0-4eab-836d-b90c1952a36d



- Breadcrumb Grenade: it explodes



https://github.com/t-kadre/Game-of-Life/assets/106656556/df3fbf8d-4506-473d-8d42-ed440b2d994b





