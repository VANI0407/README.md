# Blackjack Game Simulator

## Overview
Blackjack Game Simulator is a beginner-friendly Python console application that simulates a standard game of Blackjack between a player and a dealer. The player can place a virtual bet, receive cards, choose to hit or stand, and then compare the final hand with the dealer.

The project demonstrates functions, classes, modules, lists, loops, conditional statements, randomization, input validation, exception handling, and unit testing.

## Features
- Start a new Blackjack round
- Shuffle and deal cards from a deck
- Calculate Blackjack hand values, including Ace handling
- Player actions: Hit or Stand
- Dealer automatic play according to a fixed rule
- Virtual betting and balance tracking
- Win, lose, and push/tie results
- Input validation and error handling
- Modular source-code structure
- Automated tests for core game logic

## Technologies / Tools
- Python 3
- PyCharm (development environment)
- Git and GitHub (version control)
- Python `random` module
- Python `unittest` module

## Project Structure
```text
blackjack-project/
│
├── src/
│   ├── main.py
│   ├── game.py
│   ├── card.py
│   ├── deck.py
│   ├── player.py
│   ├── dealer.py
│   └── utils.py
│
├── tests/
│   └── test_game.py
│
├── docs/
│   └── sample_output.txt
│
├── README.md
├── statement.md
└── requirements.txt
```

## Installation and Run
1. Install Python 3 on your computer.
2. Download or clone this repository.
3. Open the project folder in PyCharm.
4. Open `src/main.py`.
5. Run `main.py`.
6. Follow the instructions shown in the console.

No external packages are required.

## Testing
From the project root, run:
```bash
python -m unittest discover -s tests -v
```

The tests check:
- Card creation
- Deck size and dealing
- Blackjack hand scoring
- Ace value adjustment
- Dealer drawing rule
- Player balance updates

## Example Game Flow
```text
BLACKJACK GAME
Starting balance: ₹1000

Enter bet amount: ₹100

Your cards: 10 of Hearts, 7 of Clubs
Dealer shows: 9 of Spades

Choose: (H)it or (S)tand: S

Dealer cards: 9 of Spades, 8 of Diamonds
Dealer value: 17
Your value: 17

Result: PUSH (Tie)
Current balance: ₹1000
```

