# minor_project_aiml
# Blackjack Game

A simple command-line implementation of the classic Blackjack card game in Python.

## Description

This Python script simulates a game of Blackjack between a player and a dealer. The player can choose to hit or stand, and the dealer follows standard rules (stands on 17 or higher). The game uses a standard deck with cards valued 2-10, face cards as 10, and Aces as 11 (adjustable to 1 if needed).

## Requirements

- Python 3.x

## How to Run

1. Ensure you have Python installed on your system.
2. Run the script using the command:
   ```
   python blackjackgame.py
   ```
3. Follow the on-screen prompts to play the game.

## Game Rules

- The goal is to get as close to 21 as possible without going over.
- Face cards (Jack, Queen, King) are worth 10 points.
- Aces are worth 11 points, but can be adjusted to 1 if your total exceeds 21.
- Type 'h' to hit (draw another card) or 's' to stand (keep your current hand).
- The dealer must stand on 17 or higher.
- If you get exactly 21 with your first two cards, it's a Blackjack and you win.
- If your total exceeds 21, you bust and lose.
- Compare your final total with the dealer's to determine the winner.

## Troubleshooting

- Ensure Python is installed and accessible from the command line.
- If you encounter any issues, check that the script file is in the correct directory and run it with the full path if necessary.
