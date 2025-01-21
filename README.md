# deeps-dino
# Deep's Dino Game

Welcome to **Deep's Dino**, a fun, interactive web-based game inspired by the classic offline dinosaur game we all know and love! This game comes with a modern design, dynamic themes, and engaging gameplay.

---

## 🚀 Features

### 🌟 Gameplay Highlights
- **Jump to Avoid Obstacles:** Play as a cute dino 🦖 and jump over obstacles like cacti 🌵.
- **Dynamic Scoring:** Keep track of your score and strive to beat your high score.
- **Game Over Overlay:** A smooth game-over screen with your final score and an option to restart.

### 🌘 Day & Night Modes
- **Light Mode:** Bright and vibrant for daytime play.
- **Dark Mode:** A soothing dark theme with stars ✨ and shooting stars 🌠 for nighttime ambiance.
- **Toggle Button:** Easily switch between modes with the theme toggle button.

### 💾 Persistent High Score
- Your high score is saved locally on your browser, so you can always aim to beat your best!

### 🎨 Responsive Design
- **Responsive Layout:** The game adjusts beautifully to different screen sizes.
- **Modern Styling:** A polished UI with smooth animations and creative designs.

---

## 🛠️ How to Play

1. **Start the Game:** The game starts automatically when you open the webpage.
2. **Jump Over Obstacles:** Press the `Space` key to make your dino jump.
3. **Score Points:** Avoid obstacles to keep playing and increase your score.
4. **Game Over:** If you collide with an obstacle, the game ends. Use the restart button to play again.

---

## 🎮 Controls

| Action       | Key          |
|--------------|--------------|
| Jump         | `Spacebar`   |
| Toggle Theme | Click the theme toggle button |

---

## 🖌️ Customization

### Change Dino Appearance
- Modify the `content` property of `.dino::before` in the CSS to use your favorite emoji or icon.

### Adjust Obstacle Speed
- Update the `animation-duration` in the `@keyframes moveObstacle` section to increase or decrease obstacle speed.

### Add More Obstacles
- Extend the `sizes` array in the `createObstacle` function with additional heights and jump requirements.

---

## 🔧 File Structure

```plaintext
Deep's Dino
├── index.html     # The main HTML file
├── style.css      # Contains all the game styling (integrated into index.html)
├── script.js      # Contains all game logic (integrated into index.html)
```

---

## 📜 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute this game as you like.

---

### 🌟 Have fun and enjoy playing Deep's Dino! 🦖
