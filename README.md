# ⚖️ BMI Calculator
### Body Mass Index Checker with Animated Meter

> ⚠️ **DISCLAIMER:** This is a **personal learning and portfolio project**. It is **NOT** a medical tool or health advisory service. BMI results are for educational and demonstration purposes only and should not replace professional medical advice. All calculations run entirely in the browser — no data is collected, stored, or transmitted.

A modern, dark-themed BMI calculator that takes weight and height inputs, computes Body Mass Index, and displays the result on an animated color-coded meter. It features strict numeric input validation, category-based color theming, illustrative result images, and smooth form-to-result transitions — all in a single self-contained HTML file.

![Version](https://img.shields.io/badge/Version-1.0.0-4361ee)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Portfolio%20Project-F4B400)
![Responsive](https://img.shields.io/badge/Responsive-Desktop%20%26%20Mobile-2D6A4F)

---

## 🔗 Live Links

- **Live Demo:** [body-mass-index-checker.netlify.app](https://body-mass-index-checker.netlify.app/)
- **Source Code:** [github.com/Ashish22Gupta/BMI_Calculator](https://github.com/Ashish22Gupta/BMI_Calculator)

---

## ✨ Implemented Features

### 🧮 BMI Calculation
- **Standard Formula** - Computes BMI using `weight (kg) / height² (m²)`, with automatic cm-to-m conversion.
- **One-Decimal Precision** - Results are rounded via `toFixed(1)` for clean readability.
- **Four Category Classifications** - Underweight (<18.5), Normal (18.5–24.9), Overweight (25–29.9), and Obese (≥30).

### 🛡️ Robust Input Validation
- **Number-Only Enforcement** - Blocks non-numeric and non-decimal keystrokes via `keypress` prevention.
- **Single-Decimal Guard** - Strips extra dots if a user pastes or types multiple decimal points.
- **Max Limit Clamping** - Caps height at `300 cm` and weight at `600 kg` to prevent unrealistic input.
- **Positive-Value Check** - Rejects `NaN`, zero, or negative values with an alert prompt.

### 📊 Animated Result Meter
- **Color-Coded Gradient Bar** - Four segments (blue → green → amber → red) aligned to BMI ranges.
- **Sliding Pointer** - A glowing white indicator animates to the correct position via `cubic-bezier` easing.
- **Dynamic Category Color** - The BMI value and category text adopt the matching range color.

### 🎨 Visual & UX Design
- **Dark Theme Palette** - Slate-based backgrounds (`#0f172a`, `#1e293b`) with high-contrast text.
- **Category Illustrations** - Displays a matching `.webp` character image per result category.
- **Smooth View Transitions** - Form fades out and result container fades in with translate-Y motion.
- **Reset Flow** - "Calculate Again" button reverses the transition and resets the pointer.

### 📱 Responsive Design
- **Fluid Centering** - Flexbox centers the card both vertically and horizontally.
- **Max-Width Card** - `400px` cap with `20px` body padding prevents edge-touching on small screens.
- **Fluid Height** - `100dvh` keeps layout stable on mobile browsers with dynamic toolbars.
- **Mobile Input Mode** - `inputmode="decimal"` triggers the numeric keypad on smartphones.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic form markup with accessible labels |
| **CSS3** | Custom properties, gradient meter, transitions, dark theme |
| **Vanilla JavaScript** | Calculation, input sanitization, animation triggering |
| **Netlify** | Static hosting and deployment |

---

## 📁 Project Structure

```text
BMI_Calculator/
└── index.html              # Self-contained app: markup + styles + logic
