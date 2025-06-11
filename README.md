# 🧊 Rubik's Cube in HTML, CSS, and JavaScript

A 3D interactive Rubik’s Cube built using only **HTML**, **CSS**, and **Vanilla JavaScript** — no libraries or frameworks required.

## 🎯 Features

- 🎨 Pure CSS 3D cube rendering
- 🖱️ Mouse/drag controls to rotate the cube
- 🧠 Logic for rotating individual cube faces
- 🔁 Shuffle functionality
- 🌐 Works in all modern browsers

## 📦 Tech Stack

- HTML5
- CSS3 (Transforms, Transitions, 3D Perspective)
- JavaScript (DOM, Events, Cube Logic)

## 🚀 Getting Started

### 📁 Clone the Repository

```bash
git clone https://github.com/yourusername/rubiks-cube-js.git
cd rubiks-cube-js
```

### ▶️ Run the App

Open `index.html` in your browser:

```bash
start index.html    # Windows
open index.html     # macOS
```

Or just drag and drop the file into your browser.

## 📂 Project Structure

```
rubiks-cube-js/
│
├── index.html         # Main HTML structure
├── style.css          # Cube styling and animations
├── script.js          # Cube logic and interaction
└── README.md          # Project documentation
```

## 🎮 Controls

- **Drag mouse** to rotate the entire cube in 3D
- **Click on cube faces** to rotate them (customizable)
- **Shuffle button** to randomize the cube (if implemented)

## 🧠 How It Works

- The cube is made of 27 smaller divs (`cubies`) arranged in 3D using CSS transforms.
- JavaScript handles:
  - User input (mouse or buttons)
  - Cube rotations (face-wise & global)
  - Logic for maintaining cube state

## 📸 Screenshots

> *(Add screenshots in `screenshots/` folder and reference here)*

## 🚧 Future Improvements

- [ ] Add keyboard controls
- [ ] Add solve algorithm (auto-solver)
- [ ] Save/Load cube state
- [ ] Improve mobile touch support
- [ ] Timer & leaderboard

## 🧩 Inspiration

This project was inspired by the mechanics and visual appeal of real Rubik’s Cubes. The goal is to simulate that in the browser as closely as possible.

## 📄 License

MIT License. Free to use and modify with credit.

## 🙌 Acknowledgements

- CSS Tricks – 3D Transforms
- MDN Web Docs – CSS Perspective, JavaScript Events
