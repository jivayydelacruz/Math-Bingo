# Math Bingo - Unity 2D Game

Welcome to **Math Bingo**, a fun and learning 2D game, built with Unity! Players have to solve math problems in order to fill in their bingo cards. There's a combination of fun in playing bingo with solving a math problem.

---
 
## Features
 
**Rolling Two Dice**: Every player has his/her dice that is rolled generating the numbers from 1 to 6.
- It contains a variety of math topics with a strong focus on multiplication and provides options to add, subtract, and divide in future updates.
- It has multiple winning patterns including horizontal line, vertical line, and diagonal.
- Social and multiplayer mode: it allows the user to compete with friends. Whoever gets the winning pattern first is declared the winner.
- It provides enticing audio feedback for the correct/incorrect answers as well as bingo wins.
- **Randomized Questions:** Elementary school math problems with the least repetition.
- **Multiple Attempts for Incorrect Answers:** Players get multiple chances until they get the problem right.

---

## How to Play

1. Start the game.
2. Roll your dice to get numbers for the math problems.
3. Solve the math problems that appear on the screen.
4. Click the correct answer to mark numbers on your bingo card.
5. Get a row, column, or diagonal to win!
6. Be the fastest to achieve a bingo in multiplayer mode!

---

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/jivayydelacruz/Math-Bingo.git
   ```
2. Open the project in Unity (version 2022.3.46f1).
3. Build and run the project.
---

## Development

### Requirements

- **Unity Editor:** Version 2022.3.46f1.
- **Unity Modules:** Ensure the following modules are installed:
  - 2D Game Kit
  - Build Support for your target platform (Android).

### Project Structure

```
Math-Bingo/
├── Assets/
│   ├── Scripts/           # Game logic and UI scripts
│   ├── Sprites/           # 2D assets and animations
│   ├── Scenes/            # Game scenes (Main Menu, Game, etc.)
│   └── UI/                # UI prefabs and settings
├── ProjectSettings/       # Unity project settings
└── README.md              # Project documentation
```

### Adding New Features

1. **To Add a New Math Mode:**
- Write a new script for math logic in `Scripts/MathModes/`.
   Update the game manager to add the new mode.

2. **To Customize Graphics:**
   Add new assets to the `Sprites/` folder.
   Update the UI or game scene accordingly.

---

## Contribution Guidelines

For collaborators:

1. Fork or clone this repository.
2. Create a feature branch:
   `
git checkout -b feature/new-feature
   `
3. Commit your changes and push them:
   `
   git push origin feature/new-feature
   `
4. Create a pull request to the dev branch on GitHub.

---

Have fun and enjoy playing Math Bingo! 
