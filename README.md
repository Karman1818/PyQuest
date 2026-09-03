# PyQuest 🐍✨

> **Learning to code has never been easier.**  
> PyQuest is an engaging, interactive educational web platform designed to introduce young learners and beginners to the fundamentals of Python programming through gamified quizzes, memory exercises, and creative drawing tools.

---

## 🚀 Overview

**PyQuest** combines interactive learning with gamified web experiences. Built with modern HTML5, CSS3, and JavaScript, the application provides an intuitive and friendly environment where students can test their Python knowledge, sharpen memory skills with a card-matching training game, and unleash their creativity with an HTML5 canvas drawing tool.

---

## ✨ Features

- 🧠 **Interactive Python Quiz (`Learn`)**
  - Instant real-time feedback with visual indicators (green/red).
  - Multi-choice questions covering Python fundamentals (`def`, `bool`, `len()`, comments, data structures).
  - Dynamic score tracking and restart functionality.

- 🃏 **Memory Card Game (`Train`)**
  - Themed card-matching memory game.
  - Built with jQuery & ES6 JavaScript for smooth card flip animations.
  - Integrated turn counter and victory detection.

- 🎨 **HTML5 Drawing Board (`Paint`)**
  - Interactive canvas for creative expression.
  - Customizable stroke color picker and brush width adjuster.
  - Instant canvas clear action.

- 🌗 **Dark / Light Mode & Modern UI**
  - Built-in theme switcher (`swapColors()`).
  - Parallax scrolling header and dynamic scroll-triggered navbar.
  - Intersection Observer animations for feature cards and technology badges.

- 🔐 **User Authentication Interfaces**
  - Clean, responsive layouts for **Login**, **Sign Up**, and **Password Recovery**.
  - Social login integration placeholders (Google, Facebook, Twitter).

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Flexbox, Grid, CSS Variables, Animations), JavaScript (ES6+), jQuery 3.2.1
- **Dev Tooling**: Node.js, [servor](https://www.npmjs.com/package/servor) (Zero-config dev server with live reload)

---

## 📁 Project Structure

```text
PyQuest/
├── index.html          # Main landing page & feature overview
├── learn.html          # Interactive Python quiz page
├── learn.js            # Quiz engine & question logic
├── train.html          # Memory card game page
├── train.js            # Game mechanics & state management
├── paint.html          # HTML5 Canvas drawing board page
├── paint.js            # Painting logic, brush tools & event handlers
├── login.html          # User login page
├── signup.html         # User sign-up page
├── forgotpass.html     # Password reset page
├── forgotpass.js       # Password reset interaction logic
├── script.js           # Navigation, theme toggle & scroll observers
├── styles.css          # Global stylesheet, animations & themes
├── jquery-3.2.1.min.js # jQuery library for game DOM manipulation
├── img/                # Graphics, card icons & technology badges
└── package.json        # NPM configuration and scripts
```

---

## ⚡ Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Karman1818/PyQuest.git
   cd PyQuest
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the local development server:**
   ```bash
   npm start
   ```

4. **Open in browser:**  
   Navigate to `http://localhost:8080` (or the port specified by `servor` in your console) to explore PyQuest!

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📬 Contact & Support

Created by **[Karman1818](https://github.com/Karman1818)**.  
If you enjoyed PyQuest, feel free to give the repository a ⭐️!