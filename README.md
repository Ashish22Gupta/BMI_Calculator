# BMI Calculator (Body Mass Index)

A modern, interactive, and responsive BMI Calculator designed to help users easily calculate their Body Mass Index based on their weight and height. The application provides a visual meter, color-coded results, and helpful character illustrations to make the experience engaging and easy to understand.

## 🚀 Live Demo
*(Add your Netlify link here once you deploy the latest version)*
https://body-mass-index-checker.netlify.app/

## ✨ Features

- **Interactive Meter:** A smooth sliding pointer animates across a color-coded gradient (Underweight, Normal, Overweight, Obese) to visually show where the user's BMI falls.
- **Smart Input Validation:** 
  - Prevents users from typing letters or invalid characters.
  - Allows decimal numbers (e.g., `175.75`).
  - Automatically restricts unrealistic values (Height max: 300cm, Weight max: 600kg).
- **Dynamic Results:** The result screen displays a large, color-coded BMI number and category.
- **Character Illustrations:** Displays a visual representation (image) matching the user's BMI category.
- **Seamless UX:** Hides the input form when showing the result to keep the interface clean. The "Calculate Again" button returns the user to the form without clearing their previous inputs.
- **Responsive Design:** Fully optimized for both desktop and mobile devices.

## 🛠️ Built With

- **HTML5** - Semantic structure.
- **CSS3** - Custom properties (variables), Flexbox, CSS Gradients, and Keyframe animations.
- **Vanilla JavaScript** - Real-time input validation, calculation logic, and DOM manipulation (no external libraries required).
