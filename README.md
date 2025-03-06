# Games

## Overview
This repository contains a collection of classic games built using Tkinter (Python) and web technologies (HTML, CSS, JavaScript). The games included are:
- Tic-Tac-Toe (Tkinter)
- Hangman (Tkinter)
- Sliding Number Puzzle (Tkinter)
- Minesweeper (HTML, CSS, JavaScript)

## Project Structure
```
Games
|-- Minesweeper
|   |-- Images
|   |   |-- <Images go here>
|   |-- index.html
|   |-- style.css
|   |-- script.js
|
|-- Hangman
|   |-- img
|   |   |-- <Images go here>
|   |-- app.py
|
|-- TicTacToe
|   |-- app.py
|
|-- Sliding Number Puzzle
|   |-- game_state.txt
|   |-- main.py
|   |-- preview.png
```

## Features
- Simple and interactive UI for all games.
- Fully functional game logic with win/loss conditions.
- Easy to modify and extend.

## Prerequisites
### For Tkinter Games:
- Python 3.x
- Tkinter (usually included with Python)

### For Minesweeper:
- Modern web browser (Chrome, Firefox, Edge, etc.)

## Installation & Usage
### Running Tkinter Games
1. Clone the repository:
   ```sh
   git clone https://github.com/Jotunn9025/Games
   ```
2. Navigate to the game directory before running the game:
   ```sh
   cd Games/TicTacToe
   python app.py  # Tic-Tac-Toe
   ```
   ```sh
   cd ../Hangman
   python app.py  # Hangman
   ```
   ```sh
   cd ../"Sliding Number Puzzle"
   python main.py  # Sliding Number Puzzle
   ```

### Running Minesweeper
1. Navigate to the `Minesweeper` folder:
   ```sh
   cd ../Minesweeper
   ```
2. Open `index.html` in a web browser.
