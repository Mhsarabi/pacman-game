# Pacman AI Search Algorithms

An AI-based Pacman project focused on solving navigation and food-collection problems using classical search algorithms.

The project explores how different search strategies can be applied to the Pacman environment to find paths through a maze and achieve specific goals.

## Overview

Pacman is a maze-based environment where an agent must navigate through corridors, avoid obstacles, and collect food.

The goal of this project is to implement and explore AI search algorithms that enable Pacman agents to solve navigation problems and find suitable paths toward their objectives.

## Search Algorithms

The project focuses on classical search strategies, including:

- **Depth-First Search (DFS)**
- **Breadth-First Search (BFS)**
- **Uniform Cost Search (UCS)**
- **A* Search**

These algorithms provide different approaches to exploring the maze and finding paths to desired locations.

## Project Structure

```text
pacman-game/
├── layouts/                 # Pacman maze layouts
├── test_cases/              # Search algorithm test cases
├── autograder.py            # Automated grading
├── commands.txt             # Example execution commands
├── game.py                  # Core game mechanics
├── ghostAgents.py           # Ghost agent implementations
├── keyboardAgents.py        # Keyboard-controlled agents
├── layout.py                # Maze layout handling
├── pacman.py                # Main game entry point
├── pacmanAgents.py          # Pacman agent implementations
├── search.py                # Search algorithm implementations
├── searchAgents.py          # Search-based Pacman agents
├── util.py                  # Utility data structures
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.x

### Clone the Repository

```bash
git clone https://github.com/Mhsarabi/pacman-game.git
cd pacman-game
```

### Run the Game

Start the Pacman environment:

```bash
python pacman.py
```

To see available command-line options:

```bash
python pacman.py -h
```

## Testing

The repository includes test cases and an autograder for evaluating search algorithm implementations.

Run the autograder with:

```bash
python autograder.py
```

Refer to `commands.txt` for additional execution examples and available project commands.

## Learning Objectives

- Understanding classical AI search strategies.
- Exploring state-space search in maze environments.
- Comparing different approaches to pathfinding.
- Applying search algorithms to practical navigation problems.
- Understanding how search-based agents interact with an environment.

## License

This project is intended for educational purposes.
