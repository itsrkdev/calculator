# 🧮 Smart Calculator | Vanilla JS

A sleek and responsive calculator designed for fast and accurate basic arithmetic. This project focuses on handling user inputs and mathematical evaluations using JavaScript.

🌐 **Live Demo:** https://itrkcal.netlify.app

---

## ✨ Key Features
- **Arithmetic Operations:** Addition, Subtraction, Multiplication, and Division.
- **Smart Evaluation:** Uses JavaScript's evaluation logic to handle complex expressions.
- **Responsive Layout:** Beautifully designed using **CSS Grid**, making it look like a real physical calculator on all devices.
- **Input Validation:** Prevents multiple decimal points and handles clear (AC) and delete (DEL) actions.
- **Dark/Modern UI:** High-contrast buttons for better visibility and user experience.

---

## 🛠️ Tech Stack
- **Frontend:** HTML5
- **Styling:** CSS3 (Custom Properties & Grid)
- **Logic:** Vanilla JavaScript (ES6+)

---

## ⚙️ How It Works (The Core Logic)
1. **Input Handling:** Captures button clicks and updates the display string.
2. **Evaluation:** Uses a robust logic to calculate the string expression.
   ```javascript
   // Example logic snippet
   function calculate() {
       try {
           display.value = eval(display.value);
       } catch (error) {
           display.value = "Error";
       }
   }
