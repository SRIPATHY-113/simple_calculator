# Simple Calculator Web Application

https://sripathy-113.github.io/simple_calculator/
A clean, responsive, and minimalist web-based calculator built using pure HTML, CSS, and vanilla JavaScript. The application uses modern CSS Grid for a pixel-perfect button layout and features interactive user feedback, dynamic input evaluation, and basic error handling for edge cases.

---

## 🚀 Key Features

* **Real-time Input Appending:** Smooth text injection into the display panel supporting multi-digit configurations and floating-point computations.
* **Modern CSS Grid Layout:** Clean 4-column dynamic grid system adapting flawlessly to both hover interactions and mobile clicks.
* **Smart Zero Handling:** Intuitively replaces the default initial placeholder `"0"` upon a first number input, but permits decimal continuations (e.g., `0.5`).
* **Robust Error Interception:** Uses a `try-catch` safety block to flag faulty expressions or division-by-zero math infinity rules, showing a graceful `"Error"` message before resetting.
* **Micro-Animations:** Fluid visual transitions (`0.2s` hover effects) and vibrant distinct gradients applied to critical call-to-action triggers like the Equals (`=`) and Clear (`C`) buttons.

---

## 📦 System Architecture & Technology Stack

* **Structure:** `HTML5` (Semantic elements like `<button>`, `<div>`)
* **Styling Engine:** `CSS3` (CSS Grid `repeat(4, 1fr)`, CSS Flexbox alignment, Linear Gradients, Box-shadow profiles)
* **Logic Framework:** `Vanilla JavaScript (ES6)` (DOM Query selectors, TextContent manipulators, Conditional evaluation, Window timeouts)

---

## ⚙️ Underlying Logic & Functional Design

### 1. The Interface Layout (`CSS Grid`)
The grid setup inside the `.buttons` wrapper distributes rows predictably across fractional spacing:
```css
.buttons {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 10px;
}
