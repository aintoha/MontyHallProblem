# 🐐 The Monty Hall Problem Explained

Welcome to this interactive explanation of the **Monty Hall Problem**—one of the most famous and counter-intuitive probability puzzles in mathematics! 

## 📺 The Setup
Imagine you are on a game show, and you're given the choice of three doors:
- Behind **one door** is a brand new **Car** 🚗
- Behind the **other two doors** are **Goats** 🐐🐐

The game plays out in three steps:
1. **You choose a door** (let's say Door 1).
2. **The Host (who knows what's behind the doors)** opens a different door (let's say Door 3), revealing a goat.
3. **The Host asks:** *"Do you want to stick with your first choice (Door 1), or switch to the remaining closed door (Door 2)?"*

**The big question:** Is it to your advantage to switch your choice?

---

## 💡 The Answer
**Yes. You should ALWAYS switch.** 
- If you **STAY** with your initial choice, your chance of winning is **1/3 (33.3%)**.
- If you **SWITCH**, your chance of winning doubles to **2/3 (66.7%)**.

---

## 🧠 Why? (The Intuitive Explanation)

Human brains naturally assume that once there are only two doors left, it's a 50/50 chance. Here is why that is false:

### 1. The Host is Not Random
When you make your first choice, there is a **1/3 chance** you picked the car, and a **2/3 chance** the car is behind one of the *other* two doors. 

The host's action of opening a goat door **does not change the 1/3 probability of your initial pick**. Instead, because the host is *forced* to avoid the car and reveal a goat, all of that **2/3 probability** collapses onto the remaining unopened door.

### 2. The 100-Doors Thought Experiment
Imagine there are **100 doors**. 
1. You pick Door 1. (You have a **1/100** chance of being right).
2. The host, who knows where the car is, opens **98 doors**—all containing goats.
3. Only Door 1 (your pick) and Door 73 are left closed.

*Would you switch?* Of course! It is highly unlikely you guessed right on the first try (1%). The host just filtered out 98 bad options for you, meaning Door 73 holds a **99% chance** of being the winner.

---

## 📊 The Mathematical Proof (Conditional Probability)

Let's look at all possible scenarios if you decide to **SWITCH** every time:

| Where is the Car? | Your Initial Pick | Host's Forced Action | Outcome if you SWITCH |
| :--- | :--- | :--- | :--- |
| **Behind Door 1** *(1/3)* | Door 1 (Car) | Opens Door 2 or 3 | **LOSE** ❌ |
| **Behind Door 2** *(1/3)* | Door 1 (Goat) | MUST open Door 3 | **WIN** 🚗 |
| **Behind Door 3** *(1/3)* | Door 1 (Goat) | MUST open Door 2 | **WIN** 🚗 |

As you can see, the only time you lose by switching is if you guessed the car correctly on your very first try—which only happens 33.3% of the time. In the other 66.7% of scenarios, switching guarantees a win!

---

## 💻 Try it Yourself: https://aintoha.github.io/MontyHallProblem/
