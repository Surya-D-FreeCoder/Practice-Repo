# Tic Tac Toe - Java Console Game

This is a simple **Tic Tac Toe** game implemented in **Java**, designed to be played by two players via the console.

## 🎮 Game Features

- 2-player mode (Player X and Player O)
- Simple text-based interface
- Automatic turn switching
- Win detection for rows, columns, and diagonals
- Input validation for occupied cells

## 🛠️ How It Works

- The game board is a 3x3 grid represented using a 2D char array.
- Players take turns entering their desired row and column positions (0-based index).
- The game checks after every move if a player has won.
- If a player tries to place a mark in an already occupied cell, they are prompted to try again.

## 📦 Requirements

- Java 8 or later
- A Java compiler (e.g., `javac`) and terminal/IDE

## 🚀 How to Run

1. Save the code in a file named `Main.java`
2. Open terminal or command prompt and navigate to the file location
3. Compile the program:
   ```bash
   javac Main.java
