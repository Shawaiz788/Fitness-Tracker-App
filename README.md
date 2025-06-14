# 🏋️ Fitness Console App (C++)

A powerful and interactive **console-based fitness app** built in C++. This project combines **workout planning**, **progress tracking**, **BMI/BMR calculators**, **water intake monitoring**, and **healthy diet recipes** — all in a single app, accessible via your terminal.

---

## 📌 Features

* 👤 **User Accounts**

  * Register and log in with personal details
  * View and update user information

* 🏃 **Exercise Plans**

  * 8 predefined workouts with instructions and timers
  * Custom workout plans with repeatable sequences
  * Real-time exercise simulation and XP-based leveling

* 📈 **Progress Tracker**

  * Visual level progress bar
  * XP calculated by exercise type
  * Progress stored per user in `Progress.txt`

* 🥗 **Diet Recipes**

  * Breakfast, lunch, and dinner recipes
  * Nutrient-rich, fitness-oriented meal ideas

* 💧 **Water Intake Tracker**

  * Calculates recommended intake based on weight
  * Validates daily water consumption

* ⚖️ **BMI & BMR Checkers**

  * Personalized BMI/BMR calculators
  * Tracker for account-based BMI using stored data

* 🏅 **Achievements System**

  * 10 bonus titles unlocked through fitness levels

* 🌟 **Daily Motivation**

  * Displays a motivational quote every time the app launches

---

## 📦 File Structure

```
├── fitness.cpp         # Main application logic
├── Ascii.h             # ASCII rendering utility
├── Accounts.txt        # Stores user account information
├── Progress.txt        # Stores workout XP & levels
├── temp.txt            # Temporary file for updates
```

---

## ⚙️ Requirements

* **Windows OS** (uses `windows.h` and console coloring)
* **C++ Compiler** (e.g., MSVC or MinGW)

---

## 🛠️ How to Compile and Run

### Compile using g++:

```bash
g++ fitness.cpp -o FitnessApp
```

> Make sure `Ascii.h` is in the same directory as `fitness.cpp`.

### Run:

```bash
./FitnessApp
```

---

## ✨ Sample Screens

* ASCII-rendered **main menu**
* Color-coded **progress bar**
* Motivational splash at startup
* Guided instructions for each workout

---

## 🔐 User Data

* `Accounts.txt`: Stores registered users (username, password, weight, height, etc.)
* `Progress.txt`: Tracks XP and levels
* Data is persisted between sessions

---

## 🙌 Credits

Developed with care in **C++**, using:

* File handling
* OOP (classes, inheritance, polymorphism)
* Console UI rendering
* Real-time simulation with threads

---
