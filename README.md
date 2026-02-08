# 🌓 Lights On / Lights Off UI

A super smooth, interactive Dark/Light mode toggle designed with pure **Vanilla Web Technologies**. No frameworks, no bloat—just clean code and cool transitions.

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=opensource&logoColor=white)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-blue?style=for-the-badge&logo=github&logoColor=white)
![Vibe](https://img.shields.io/badge/Vibe-Chill-purple?style=for-the-badge&logo=sparkles&logoColor=white)

## 🎨 Design Preview

Imagine a sleek interface that glides between day and night.

> **Current State:** The project features a deep blue "Dark Mode" by default and transitions gracefully to a soft white "Light Mode" with a single click.

*(You can replace this text with a screenshot of your project later!)*

## 🛠️ Built With

This project relies on the holy trinity of web development:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## ⚡ How It Works

![DOM](https://img.shields.io/badge/DOM-Manipulation-orange?style=for-the-badge&logo=web&logoColor=white)

1.  **State Management:** The JavaScript listens for a click event on the main button.
2.  **Class Toggling:** It adds or removes the `.lights-on` class from the `<body>`.
3.  **CSS Transitions:** We use `transition: 0.8s ease` to make the background and text colors morph slowly instead of snapping instantly.
4.  **Dynamic Text:** The button reads the state of the page and updates its own text ("Turn Lights On" vs "Turn Lights Off").

## 🏃‍♂️ How to Run

### 📂 No Installation Needed!

Since this is a static site, you don't need `npm`, `node`, or python.

1.  **Clone or Download**
    ```bash
    git clone https://github.com/your-username/lights-on-off.git
    ```
2.  **Open the Folder**
    Navigate to the project directory.
3.  **Launch**
    Simply double-click `index.html` to open it in Chrome, Firefox, Safari, or Edge.

## 🎨 How to Modify

Want to tweak the colors or speed? It's easy.

**To Change Colors:**
Open `style.css` and look for:
```css
/* Dark Mode (Default) */
body { background-color: #1a1a2e; } 

/* Light Mode */
body.lights-on { background-color: #f0f0f0; }
