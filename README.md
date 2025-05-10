# 🐍 Snake Game

A modern implementation of the classic Snake game using Pygame in Python. This game brings the nostalgic arcade experience to your computer with smooth controls, score tracking, and a clean interface.


## ✨ Features

- 🎮 Classic snake gameplay with modern implementation
- 📊 Real-time score tracking
- 🎯 Precise controls using arrow keys
- 🎨 Clean, minimalist visual design
- 🔄 Screen wrapping for continuous gameplay
- 💥 Collision detection with self
- 🔄 Automatic game reset on collision
- 🎯 Random food spawning
- ⚡ Smooth 60 FPS gameplay

## 🛠️ Technical Requirements

- Python 3.6 or higher
- Pygame 2.0.0 or higher
- Modern operating system (Windows, macOS, or Linux)

## 🚀 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/snake-game.git
cd snake-game
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 🎮 How to Play

1. Launch the game:
```bash
python main.py
```

2. Controls:
- ⬆️ Up Arrow: Move snake upward
- ⬇️ Down Arrow: Move snake downward
- ⬅️ Left Arrow: Move snake left
- ➡️ Right Arrow: Move snake right
- ESC: Quit game

3. Game Rules:
- 🎯 Eat the red food to grow longer
- 💥 Avoid colliding with yourself
- 🔄 Snake wraps around screen edges
- 📈 Score increases with each food eaten
- 🎮 Game automatically resets on collision

## ⚙️ Game Configuration

The game can be customized by modifying these constants in `main.py`:
- Window Size: 800x600 pixels
- Grid Size: 20x20 pixels
- Game Speed: 10 FPS
- Colors: Customizable RGB values

## 📁 Project Structure

The game is organized into two main classes:
- `Snake`: Handles snake movement, growth, and rendering
- `Food`: Manages food placement and rendering

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the classic Snake game
- Built with [Pygame](https://www.pygame.org/)
