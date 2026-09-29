# 🃏 Blackjack Game — Python

A **command-line Blackjack game built with Python** that simulates a simplified version of the classic casino card game.

The player competes against the dealer by drawing cards and making strategic decisions based on their hand. The project focuses on implementing game logic, handling different game states, and working with lists, functions, loops, and conditional statements.

## 🎮 Features

* 🃏 Deal cards to the player and dealer
* 🎯 Calculate hand scores
* 👤 Player actions: **Hit** or **Stand**
* 🤖 Dealer automatically draws according to game rules
* 🅰️ Handles Ace values as **1 or 11**
* 💥 Detects Blackjack
* ⚠️ Detects busts
* 🏆 Determines the winner
* 🔄 Allows multiple rounds
* 📊 Displays the player's and dealer's hands
* 🖥️ Interactive command-line gameplay

## 🧠 Game Rules

The objective is to get a hand value as close to **21** as possible without going over.

### Card Values

```text
Number cards → Face value
J, Q, K      → 10
A            → 1 or 11
```

### Gameplay

```text
Start Game
    ↓
Deal Initial Cards
    ↓
Calculate Scores
    ↓
Player chooses:
  ├── Hit → Draw another card
  └── Stand → End player's turn
    ↓
Dealer plays automatically
    ↓
Compare Scores
    ↓
Display Result
    ↓
Play Again / Exit
```

## 💻 Example

```text
================================
        BLACKJACK
================================

Your cards: ['10', '6']
Your score: 16

Dealer's first card: ['K']

Do you want to 'hit' or 'stand'? hit

Your cards: ['10', '6', '4']
Your score: 20

Do you want to 'hit' or 'stand'? stand

Dealer's cards: ['K', '7']
Dealer's score: 17

🎉 You win!
```

## 🛠️ Tech Stack

* **Python 3**
* Python Standard Library
* Command Line / Terminal

## 📚 Python Concepts Practiced

This project helped me practice:

* Functions
* Lists
* Loops
* Conditional statements
* String manipulation
* Random number generation
* User input
* Input validation
* Boolean logic
* Game-state management
* Modular programming
* Problem-solving

## 🎯 Project Objective

The goal of this project was to build an interactive Python application while applying programming fundamentals to a complete game.

It combines multiple concepts into one project, including **data handling, randomization, decision-making, loops, functions, and game logic**.

## 🔮 Future Improvements

Possible improvements for future versions:

* 💰 Add betting and virtual chips
* 📈 Add player statistics
* 🏆 Add a win/loss tracking system
* 🎰 Add multiple players
* 🃏 Use a realistic 52-card deck
* 💾 Save player statistics
* 🎨 Create a graphical user interface
* 🔊 Add sound effects
* ⚙️ Add configurable game rules

## 👩‍💻 Author

**Carla Rizk**

Computer Science Student | Technical Support Specialist | Aspiring Software Developer

---

⭐ **A Python project focused on game logic, problem-solving, and building an interactive command-line application.**
