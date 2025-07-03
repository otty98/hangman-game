# 🎯 Hangman Game

A modern, interactive hangman game built with HTML, CSS, and JavaScript. Guess the word letter by letter before the hangman is fully drawn!

## 🎮 Play the Game

**[🚀 Play Now on GitHub Pages](https://otty98.github.io/hangman-game/)**


## 📸 Screenshots

![image](https://github.com/user-attachments/assets/c06dcd50-4a87-46da-8f81-46a659a34d65)
![image](https://github.com/user-attachments/assets/04bd0b2d-df62-4305-ae6f-b58e1195c638)



## ✨ Features

### 🎯 Game Mechanics
- **Classic hangman gameplay** with 6 chances to guess
- **Random word selection** from curated word lists
- **Progressive hangman drawing** with each wrong guess
- **Real-time feedback** on correct and incorrect guesses

### 🎨 Visual Design
- **Modern gradient background** with smooth animations
- **Responsive design** that works on all devices
- **Color-coded letter tracking** (green for correct, red for incorrect)
- **Smooth transitions** and hover effects
- **Win/lose animations** with bounce and shake effects

### 🎪 Word Categories
- **Animals** - Elephant, Giraffe, Penguin, Dolphin, and more
- **Fruits** - Pineapple, Strawberry, Watermelon, Blueberry, and more
- **Countries** - Australia, Switzerland, Indonesia, Argentina, and more
- **Sports** - Basketball, Volleyball, Swimming, Football, and more

### 🎮 User Experience
- **Keyboard support** - Press Enter to guess letters
- **Auto-uppercase** input for consistency
- **Input validation** to ensure valid letters only
- **Duplicate guess prevention** 
- **Game statistics** showing wrong guesses and category
- **New game button** for multiple rounds

## 🚀 Getting Started

### Option 1: Play Online
Simply visit the [GitHub Pages link](https://otty98.github.io/hangman-game/) to play instantly!

### Option 2: Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/hangman-game.git
   cd hangman-game
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - Or use a local server like Live Server in VS Code

3. **Start playing!**

## 🎯 How to Play

1. **Start the game** - A random word is selected from one of four categories
2. **Guess letters** - Type a letter and click "Guess Letter" or press Enter
3. **Track your progress** - Correct letters appear in the word, wrong letters build the hangman
4. **Win or lose** - Guess the complete word before making 6 wrong guesses
5. **Play again** - Click "New Game" to start another round

## 🛠️ Technical Details

### Built With
- **HTML5** - Structure and semantics
- **CSS3** - Styling, animations, and responsive design
- **Vanilla JavaScript** - Game logic and interactivity

### Key Features
- **No external dependencies** - Pure HTML, CSS, and JavaScript
- **Responsive design** - Works on desktop, tablet, and mobile
- **Modern ES6+** syntax with proper error handling
- **Clean, maintainable code** with clear function separation

### Browser Support
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 📁 Project Structure

```
hangman-game/
├── index.html      
├── README.md          
└── assets/             
    └── screenshot.png
```

## 🎮 Game Rules

- You have **6 wrong guesses** before the game ends
- Each wrong guess adds a body part to the hangman
- **Win** by guessing all letters in the word
- **Lose** when the hangman drawing is complete
- Letters are **case-insensitive** (automatically converted to uppercase)
- **Duplicate guesses** are prevented and won't count against you

## 🎨 Customization

Want to modify the game? Here are some easy customizations:


### Change Difficulty
Modify the `wrongGuesses` limit or add more hangman stages in the `hangmanStages` array.

### Styling
All styles are in the `<style>` section - easily customizable colors, fonts, and animations.

## 🤝 Contributing

Contributions are welcome! Here are some ideas:
- Add more word categories
- Implement difficulty levels
- Add sound effects
- Create multiplayer mode
- Add hints system
- Implement word definitions

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the classic hangman game
- Built with modern web technologies
- Designed for educational and entertainment purposes

## 📞 Contact

- **GitHub**: [@your-username](https://github.com/otty98)
- **Email**: your.email@example.com

---

⭐ **Star this repository** if you enjoyed the game!

**[🎮 Play the Game Now](https://otty98.github.io/hangman-game/)**
