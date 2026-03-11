# ✿ Heartopia Kitchen Manager & Profit Optimizer ✿

A high-performance mathematical optimization tool designed for the **Heartopia** community. This application calculates the most profitable combinations of recipes based on your current inventory and market star probabilities.

## 🚀 Features

* **Linear Programming Engine**: Uses the `javascript-lp-solver` to handle complex multi-ingredient dependencies.
* **Hierarchical Production Flow**: Organizes "Cook" and "Use" steps into a logical factory-style tree.
* **Star Probability Scaling**: Dynamically adjusts expected revenue based on 1★ through 5★ success rates.
* **Heartopia Aesthetic**: Features a custom-designed Pastel Light Mode and a high-contrast Charcoal Dark Mode.
* **Mobile Optimized**: Responsive layout that scales from desktop browsers to mobile home-screen shortcuts.

## 🛠️ How to Use

1.  **Enter Stock**: Input your current counts for store-bought, farmed, and foraged items.
2.  **Set Probabilities**: Use the built-in guide to enter your specific star success rates.
3.  **Toggle Recipes**: Enable or disable specific dishes based on your level or preference.
4.  **Optimize**: Click the ✦ RUN OPTIMIZER ✦ button to generate a full production plan.

## 💻 Tech Stack

* **Frontend**: HTML5, CSS3 (Flexbox/Grid), Vanilla JavaScript.
* **Math Engine**: [javascript-lp-solver](https://github.com/JWally/jsLPSolver).
* **Theming**: Dynamic CSS Variable injection for Light/Dark modes.

---
*Created with care for the Heartopia community.*
