# 🌹 Midnight Velvet Rose — Interactive Flower Animation

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)

<p align="center">
  <b>An enchanting, romantic web experience featuring blooming CSS velvet roses, interactive secret love notes, ambient particle effects, and background music.</b>
</p>

</div>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Demo & Preview](#-demo--preview)
- [Project Architecture](#-project-architecture)
- [Getting Started](#-getting-started)
- [Customization Guide](#-customization-guide)
- [Browser Compatibility](#-browser-compatibility)
- [Security](#-security)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

**Midnight Velvet Rose** is a pure front-end interactive experience crafted with HTML5, advanced CSS keyframe animations, and vanilla JavaScript. 

Originally built as a classic floral animation, this project has evolved into a deeply emotional, romantic gift web app. Users are greeted with an animated glowing entrance, followed by blooming velvet roses under a starry night sky, clickable blossoms revealing sweet love letters, floating heart trails on touch/click, and a grand finale surprise modal.

---

## ✨ Key Features

- 🌹 **Midnight Velvet Rose Palette:** Multi-layered CSS gradients combining deep velvet crimson, ruby rose, and raspberry with warm gold firefly sparkles.
- 💌 **Interactive Blossom Love Notes:** Click or tap any of the blooming flower heads to open an elegant frosted-glass love letter modal with custom messages.
- 💖 **Touch & Cursor Particle Trail:** Moving the cursor or tapping on mobile spawns dynamic floating hearts (`❤️`, `💖`, `💕`, `🌹`, `✨`) powered by an HTML5 canvas particle physics engine.
- 🎶 **Floating Music Player Widget:** Seamlessly plays background music (`Floricienta.mp3`) with auto-start on user interaction and an aesthetic spinning vinyl/disc control.
- 🎆 **Grand Finale Surprise & Heart Shower:** An interactive surprise proposal/note modal with response buttons that trigger celebratory heart fireworks across the entire screen.
- 📱 **Fully Responsive:** Smooth 60fps animations optimized for desktop, tablets, and smartphones.
- ⚡ **Zero External Dependencies:** Built with pure vanilla JavaScript and CSS — lightweight, fast, and easy to deploy anywhere.

---

## 🖼️ Demo & Preview

```
[index.html] ──( Click Me )──► [FLORES.html] (Blooms Velvet Roses + Music + Love Notes + Particles)
```

| Landing Page | Interactive Bouquet |
| :---: | :---: |
| Glowing "HELLO" greeting with glowing red CTA button | Blooming Velvet Roses with secret notes & floating particles |

---

## 📁 Project Architecture

```plaintext
Flower-animation-main/
├── css/
│   ├── interactive.css    # Styles for love modals, particles, music widget & hint badges
│   ├── main.css           # Core flower animation keyframes & velvet rose theme
│   └── style.css          # Landing page styles (glowing HELLO & red CTA button)
├── img/
│   ├── Floricienta.mp3    # Romantic background music track
│   └── flowers.png        # Project favicon / icon
├── js/
│   └── interactive.js     # Particle engine, flower clicks, modal handlers & fireworks
├── FLORES.html            # Main interactive bouquet scene
├── index.html             # Landing entrance page
├── LICENSE                # MIT License
├── README.md              # Project documentation
└── SECURITY.md            # Security policy & reporting guidelines
```

---

## 🚀 Getting Started

### Prerequisites
All you need is a modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).

### Local Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/gmpsankalpa/Flower-animation.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Flower-animation
   ```

3. **Launch the application:**
   - Double-click `index.html` to open it in your default browser, or
   - Use a local development server (such as VS Code *Live Server* or Python `python -m http.server 8000`).

---

## 🎨 Customization Guide

### 1. Customizing Love Notes
Open [`js/interactive.js`](js/interactive.js#L11-L30) and modify the `loveNotes` object with your own messages:
```javascript
const loveNotes = {
  1: {
    title: "My Peaceful Garden",
    message: "“Your personalized message here...”",
    icon: "🌹"
  },
  // Add or change notes for flowers 2 and 3
};
```

### 2. Changing Background Music
Replace `img/Floricienta.mp3` with your favorite `.mp3` file, or update the file path in [`js/interactive.js`](js/interactive.js):
```javascript
const audio = new Audio('./img/your-song.mp3');
```

### 3. Customizing Colors
Modify the root CSS variables in [`css/interactive.css`](css/interactive.css) and [`css/main.css`](css/main.css):
```css
:root {
  --primary-rose: #ff2a6d;
  --deep-velvet: #8b0038;
  --soft-rose: #ff758c;
  --gold-glow: #ffd166;
}
```

---

## 🌐 Browser Compatibility

| Browser | Supported Version |
| :--- | :--- |
| **Google Chrome** | 88+ ✅ |
| **Mozilla Firefox** | 85+ ✅ |
| **Apple Safari** | 14+ ✅ |
| **Microsoft Edge** | 88+ ✅ |
| **Mobile Browsers (iOS / Android)** | All modern versions ✅ |

---

## 🔒 Security

For details on security practices, supported versions, and how to report vulnerabilities responsibly, please review our [SECURITY.md](SECURITY.md).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.