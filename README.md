<div align="center">

# 🌙 Dark Mode Login Page

**A modern glassmorphic login UI with floating-label inputs, built in pure HTML & CSS.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)

</div>

---

## 📖 Overview

A self-contained, single-page **login screen** demonstrating a clean glassmorphism aesthetic on a dark purple background. The card uses backdrop blur, soft shadows, and animated floating labels - built entirely with native CSS, with no JavaScript and no external libraries.

## ✨ Features

- **Glassmorphism card** | semi-transparent panel with `backdrop-filter: blur()` over a solid dark backdrop
- **Floating label inputs** | labels shrink and rise above the input on focus or valid content, using `:is(:focus, :not(:invalid))`
- **CSS-only validation styling** | `required` fields get a colored focus ring; no JS validation logic needed
- **Interactive button state** | hover lift animation (`translateY`) with a color shift on the submit button
- **Fully responsive card** | fixed-width centered layout using CSS Grid (`place-items: center`)

## 🛠️ Tech Stack

- **HTML5** | semantic form markup
- **CSS3** | Grid layout, `backdrop-filter`, CSS transitions, pseudo-class-driven label animation

No build tools, frameworks, or dependencies are required.

## 🚀 Getting Started

Clone the repo and open the file directly in a browser:

```bash
git clone https://github.com/ahmedfarani/dark-mode-login-page.git
cd dark-mode-login-page
```

Then open `index.html` in any modern browser - no server or installation needed.

## 📁 Project Structure

```
dark-mode-login-page/
├── index.html     # Login form markup
└── style.css      # Glassmorphism styling, layout, and animations
```

## 🎨 Design Notes

| Element | Detail |
|---|---|
| Background | `#1e142c` (deep purple) |
| Card | `rgba(6, 5, 7, 0.19)` with 38px backdrop blur |
| Accent color | `#a544ff` → `#C084FC` on hover |
| Border radius | `40px` (card), `8px` (inputs/button) |

## 📜 License

This project is open source and available for personal or educational use.

---

<div align="center">

Built by **Ahmed Farani**

</div>