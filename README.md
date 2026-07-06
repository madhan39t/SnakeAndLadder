# 🐍🎲 Snake and Ladder Game in Java

A console-based **Snake and Ladder Simulator** developed using **Object-Oriented Programming (OOP)** concepts in Java. The game supports multiple players, snakes, ladders, dice rolling, and turn-based gameplay using a queue data structure.

This project was created as part of **Weekend Dev Challenge #57: LLD Projects** conducted by **CodeChef**.

![Java](https://img.shields.io/badge/Java-OOP-blue)
![Project](https://img.shields.io/badge/Project-Completed-brightgreen)
![CodeChef](https://img.shields.io/badge/Weekend%20Dev%20Challenge-57-orange)

---

## 🏆 About the Challenge

This project was built for **Weekend Dev Challenge #57: Low-Level Design (LLD) Projects**, organized by **CodeChef** to strengthen software design and object-oriented programming skills.


---

## 🚀 Features

* 🎲 Random dice rolling
* 🐍 Snakes that move players down
* 🪜 Ladders that move players up
* 👥 Multiplayer support
* 🔄 Turn management using Queue
* 🏆 Automatic winner detection
* 🚫 Exact dice roll required to win
* 📚 Clean and modular OOP design

---

## 📂 Project Structure

```text
SnakeAndLadder.java
│
├── Player         // Stores player details and position
├── Dice           // Generates random dice values
├── Board          // Stores snakes and ladders
├── GameEngine     // Handles game logic and turns
└── SnakeAndLadder // Main class to run the game
```

---

## 🛠 Technologies Used

* Java
* Object-Oriented Programming (OOP)
* Collections Framework

  * Queue
  * LinkedList
  * HashMap
* Random Number Generation

---

## 🧩 OOP Concepts Implemented

* Classes and Objects
* Encapsulation
* Composition
* Abstraction
* Modular Design

---

## ▶️ How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-github-username/snake-and-ladder-java.git
```

### Move to Project Directory

```bash
cd snake-and-ladder-java
```

### Compile the Program

```bash
javac SnakeAndLadder.java
```

### Run the Program

```bash
java SnakeAndLadder
```

---

## 🎮 Sample Gameplay

```text
--- Starting Snake and Ladder Simulator ---

Alice rolled a 4 and moved from 0 to 4
Yay! Alice took a ladder up to 14

Bob rolled a 6 and moved from 0 to 6

Alice rolled a 5 and moved from 14 to 19

...

Game Over! Alice wins the game!
```

---

## 🏗 Design Highlights

### Snake and Ladder Representation

A single `HashMap<Integer, Integer>` is used to represent both:

* Snakes → Higher position to lower position
* Ladders → Lower position to higher position

### Turn Management

A `Queue<Player>` is used to:

1. Remove the current player.
2. Play their turn.
3. Add them back to the queue.

This ensures proper round-robin gameplay.

---

## 🔮 Future Enhancements

* Support for more than two players
* Custom board size
* Multiple dice support
* Graphical User Interface (GUI)
* Save and Load Game
* Statistics and Scoreboard
* Human vs Computer mode

---

## 👨‍💻 Author

**MADHANKUMAR B**

Passionate Java Developer | Problem Solver | Continuous Learner


---

## 🌟 Acknowledgement

This project was developed as part of **Weekend Dev Challenge #57: LLD Projects** conducted by **CodeChef** to improve Low-Level Design and Object-Oriented Programming skills.

⭐ If you like this project, please **Star ⭐ the repository** and connect with me on CodeChef!
