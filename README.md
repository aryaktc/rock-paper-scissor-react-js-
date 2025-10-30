# 🪨✋✂️ Rock Paper Scissors Game  

[![React](https://img.shields.io/badge/React-18.0-blue?logo=react)](https://react.dev/)
[![CSS3](https://img.shields.io/badge/Style-CSS3-blueviolet?logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Deployed](https://img.shields.io/badge/Live%20Demo-aryakrockpaper.ccbp.tech-success?logo=vercel)](https://aryakrockpaper.ccbp.tech/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)]()

---

## 🌐 Live Demo
🎮 **Play Now:** [https://aryakrockpaper.ccbp.tech/](https://aryakrockpaper.ccbp.tech/)

---

## 📘 Overview
A modern, fully responsive **Rock Paper Scissors** web app built with **React.js** and styled using pure **CSS**.  
The player competes against a computer opponent, with real-time score tracking, dynamic result rendering, and an interactive rules popup.

Designed and implemented to **pass all NxtWave/CCBP automated test cases** for layout, behavior, and accessibility.  

---

## 🧠 Game Logic

| Your Choice | Opponent’s Choice | Result |
|--------------|------------------|--------|
| Rock         | Scissors         | 🟢 You Win |
| Scissors     | Paper            | 🟢 You Win |
| Paper        | Rock             | 🟢 You Win |
| Same Choice  | Same Choice      | ⚪ Draw |
| Others       | —                | 🔴 You Lose |

- 🟩 **Win:** Score increases by **+1**  
- 🟨 **Draw:** Score remains **unchanged**  
- 🟥 **Lose:** Score decreases by **–1**

---

## ✨ Features
✅ **React Functional Components + Hooks**  
✅ **Pure CSS styling** (no styled-components)  
✅ **Dynamic Gameplay** with random opponent generation  
✅ **Rules Modal Popup** (using `reactjs-popup`)  
✅ **Responsive Design** across all screen sizes  
✅ **Test Compliance** (NxtWave/CCBP)  
✅ **Deployed** on CCBP hosting → [aryakrockpaper.ccbp.tech](https://aryakrockpaper.ccbp.tech/)

---

## 🧩 Project Structure
src/
│
├── App.js
├── App.css
├── choicesList.js
│
├── components/
│ ├── ScoreBoard.js
│ ├── ScoreBoard.css
│ ├── PlayingView.js
│ ├── PlayingView.css
│ ├── ResultView.js
│ ├── ResultView.css
│ ├── RulesPopup.js
│ ├── RulesPopup.css
│
├── index.js
└── index.css


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/rock-paper-scissors.git
cd rock-paper-scissors

2️⃣ Install Dependencies
npm install

3️⃣ Start Development Server
npm start


Your app will run at 👉 http://localhost:3000

📦 Dependencies
Package	Purpose
reactjs-popup	Displays the rules popup modal
react-icons (RiCloseLine)	Close icon inside the popup
react / react-dom	Core React functionality
CSS Modules	Styling for individual components

Install them manually if needed:

npm install reactjs-popup react-icons

🎨 Design System

🎨 Colors

Element	Color Code
Background	#223a5f
Text	#ffffff
Score Box	#ffffff (text #223a5f)

🖋️ Fonts

Headings → Bree Serif

Score Value → Roboto (required for tests)

🔘 Buttons

Button	data-testid
Rock	rockButton
Paper	paperButton
Scissors	scissorsButton

🖼️ Alt Attributes

Image	alt text
Player’s choice	"your choice"
Opponent’s choice	"opponent choice"
Rules image	"rules"
