# Number Guessing Game – Networked Edition (Modified Dice Duelers)

Welcome to your **C++ Programming Assessment Task**!

This project is a modification of the original **Dice Duelers** console game.

 Instead of dice rolls, we implement a classic **number guessing game** where the **Server picks a number**, and the **Client tries to guess it**.

---

## Assignment Overview

- **Module**: C++ Programming  
- **Assessment Type**: In-Class Practical  
- **Duration**: 2 Hours  
- **Lecturer**: Rakesh Sonea

---

## Objectives

You are required to:
- Modify the existing Dice Duelers console game
- Replace the game logic with a networked number guessing game
- Apply OOP principles, functions, loops, and conditionals
- Demonstrate your ability to read, modify, and build on existing code

---

## Game Rules

- The **Server** chooses a random number between **1 and 20**
- The **Client** has **3 attempts** to guess the number
- After each guess:
  - If guess is too low → server replies `"UP"`
  - If guess is too high → server replies `"DOWN"`
  - If guess is correct → server replies `"CORRECT"`
- If the Client guesses correctly within 3 attempts → **Client wins**
- Otherwise → **Client loses**
- The Client decides whether to **play again or quit**
- If continuing, the **score is tracked** (wins and losses)

---

## How to Run

### 1. Clone the Base Project
```bash
git clone https://github.com/your-org/dice-duelers.git
cd dice-duelers
```

Or Use Github to Clone.

### 2. Open in CLion

### 3. Build and Run

- Start the server in one terminal
- Start the client in another terminal or on a second PC in the same LAN

## What to Modify

You will:

- Create or modify a function like `playGuessingGame()` in `GameManager.cpp`
- Replace the dice duel logic with your number guessing logic
- Implement loop, conditions, and tracking score based on wins/losses

## Submission Instructions

###  STEP 1 – Create Your Own GitHub Repository

1. Go to https://github.com
2. Create a **new private repository** named:
    `cpp-network-guessing-game-<YourName>`
3. Push your **modified project files** into this repo.

### STEP 2 – Submit Your Repository Link

Once done, **submit only the GitHub repo link** via the provided form or email.
 **Example**:

https://github.com/username/cpp-network-guessing-game-john



## Grading Criteria (100 Marks)

| Criteria                                       | Marks |
| ---------------------------------------------- | ----- |
| Project builds & runs                          | 10    |
| Game logic implemented as described            | 20    |
| Use of loops and conditionals                  | 20    |
| OOP design (class/function used appropriately) | 20    |
| Replay logic and score tracking                | 5     |
| Clear user input/output handling               | 15    |

**Bonus (10 marks)**: Good comments, modular code, or input validation