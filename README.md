# 🃏 BlackJack Game (Python)

A command-line Blackjack game developed in Python using object-oriented programming principles.  
The project simulates a real Blackjack game with dealer logic, ace value handling, and multi-round gameplay.

---

## 📌 Project Description

This project demonstrates the use of Python OOP concepts to build a complete Blackjack game.  
It includes realistic game rules, structured class design, and interactive user input through the terminal.

---

## 📁 File Structure
BlackJackGame.py


---

## 🎮 Features

- Object-Oriented Design (`Card`, `Deck`, `Hand`, `Game`)
- Standard 52-card deck generation
- Card shuffling and dealing logic
- Dealer AI (hits until hand value reaches 17)
- Ace value adjustment (11 or 1)
- Blackjack detection
- Bust detection
- Hidden dealer card until player stands
- Multiple rounds in a single execution
- Clean and readable terminal output

---

## 🧠 Game Rules

- Player and dealer start with two cards each
- Dealer’s first card is hidden initially
- Player can choose to **Hit** or **Stand**
- Aces count as 11 or 1 depending on hand value
- Dealer must hit until hand value is at least 17
- Blackjack beats all non-blackjack hands
- Hand value exceeding 21 results in a bust

---

## ▶️ How to Run the Game

1. Ensure Python 3 is installed
2. Open a terminal in the project directory
3. Run the following command:

```bash
python BlackJackGame.py
```

## 🕹️ Controls

- `h` or `hit` → Draw a card  
- `s` or `stand` → End your turn  

---

## 🧩 Classes Overview

### `Card`
- Represents an individual playing card with a suit and rank

### `Deck`
- Creates a standard 52-card deck  
- Shuffles cards randomly  
- Deals cards to players  

### `Hand`
- Stores cards for player or dealer  
- Calculates hand value dynamically  
- Handles Ace value logic  
- Displays cards to the terminal  

### `Game`
- Manages overall game flow  
- Handles user input  
- Controls dealer behavior  
- Determines winners  
- Supports multiple games per run

## 🧪 Sample Gameplay
Your hand:
10 of hearts
7 of spades
Value: 17

Dealer hand:
hidden
K of diamonds

Hit or Stand? (h/s):

## 🚀 Future Enhancements

Betting and balance system

Split and double-down options

Multiple players

Graphical User Interface (GUI)

ASCII card visuals

## 🛠️ Technologies Used

Python 3

Standard Library only (no external dependencies)

## 📜 License
This project is open-source and intended for educational and learning purposes.
