# ♠️ Poker Project


<img src="https://github.com/Dreamerol/Dreamerol/blob/6a3bc3cf9d4d9ddecf05e2a45a86d2ce5466b6da/ZPOCKER.jpg" alt="POCKER" style="width:100%; height:auto;">


## 🚀 Overview

This project is a console-based implementation of a simplified **Poker game**, developed as part of a programming assignment. It simulates the essential components of poker, including cards, players, and hand evaluation.

---

## 🚀 Purpose

The main goal of this project is to practice core programming concepts by building a real-world application. The project focuses on:

- Implementing game logic  
- Working with structured data (cards, deck, players)  
- Simulating interactions between different components  
- Understanding how complex systems can be broken into smaller parts  

---

## 🃏 Game Overview

This project represents a simplified version of Poker. The typical flow of the game is:

1. A standard deck of 52 cards is created  
2. The deck is shuffled randomly  
3. Each player is dealt a set of cards  
4. The program evaluates each player's hand  
5. A winner is determined based on hand rankings  

Depending on your implementation, the game may support multiple players and repeated rounds.

---

## 🧠 Core Components

### 🂡 Card

Represents a single playing card.

Each card has:
- A **rank** (2–10, Jack, Queen, King, Ace)  
- A **suit** (Hearts, Diamonds, Clubs, Spades)  

This is the basic building block of the entire game.

---

### 🃴 Deck

Represents a full deck of 52 cards.

Responsibilities:
- Generate all cards  
- Shuffle the deck randomly  
- Provide cards when dealing  

---

### 👤 Player

Represents a participant in the game.

Each player:
- Holds a hand of cards  
- Can be evaluated based on their hand  
- Competes against other players  

---

### 🎮 Game Logic

Controls the flow of the program.

Responsibilities:
- Initialize the deck and players  
- Deal cards  
- Manage turns (if implemented)  
- Evaluate hands  
- Determine the winner  

---

## 🏆 Hand Evaluation

A key part of the project is determining the strength of a player's hand.

Typical poker combinations include:

- High Card  
- Pair  
- Two Pairs  
- Three of a Kind  
- Straight  
- Flush  
- Full House  
- Four of a Kind  
- Straight Flush  

The program compares players' hands and decides the winner based on these rankings.

---

## 🛠️ Features

- ✔ Full deck simulation (52 cards)  
- ✔ Random card shuffling  
- ✔ Multiple players support (if implemented)  
- ✔ Hand ranking system  
- ✔ Winner determination  
- ✔ Console-based interaction  

---

PROJECT POCKER 10
I use Visual Studio

I have one main cpp file with all the functions for the program.

The project is about playing simple poker, so I decided to arrange the functionality into few sections:

1.I create structs which represent a card and a player.

2.The I create a function for dealing the cards, using rand() for the indexes of already dealed cards.

3.Then come the functions for evaluating the result based on the cards in every player's hand.

4.I also have a few validations functions for entering answers, or number of players.

5.In the main() function - I use while cycle for the games until the user enter No, I have used bool flags - indicating for a new game or a tie - I have also a nested for cycle - when asking every player for (r/c/f).

6.If there is a tie - we go back at the beginning of the program - new dealing - new array of dealed and the same algorhitm is executed!
