# Forge Ore Calculator

A web-based utility tool designed to optimize ore usage in the Forge. This calculator helps players determine the best 5-slot combination of ores to maximize their output multiplier.

## 🔗 [Click Here to Open the Calculator](lohsttt.github.io/afkable-calculator)
*(Replace the link above with the one generated in your Settings > Pages tab)*

## ✨ Features

* **Best Combination Logic:** Automatically sorts your inventory and selects the top 5 highest-value ore stacks.
* **Result Range:** Calculates the final Forge outcome range (50% to 100% of the total multiplier).
* **Compact UI:** Clean, dark-themed interface designed to fit many items on screen without excessive scrolling.
* **Ore Filtering:** A settings menu allows you to hide ores you don't collect or care about.
* **Auto-Save:** Your filter settings are saved automatically so you don't have to re-select them every time you visit.

## 🚀 How to Use

1.  **Open the Website:** Click the link at the top of this Readme.
2.  **Filter Ores:** Click the `⚙️ Filter Ores` button at the top. Uncheck any ores you do not currently farm or own to clean up the view.
3.  **Input Amounts:** Type the quantity of items you have for each ore in the input box.
4.  **View Results:**
    * The **Best Combination** panel on the right (or bottom on mobile) will update instantly.
    * The **Forge Result Multiplier** shows your expected outcome range (e.g., `100x - 200x`).

## 🧮 How It Works

The calculator uses the following logic:
1.  Takes the user input quantity.
2.  Multiplies quantity by the Ore's base multiplier (e.g., Cosmic Clutter = 200x).
3.  Sorts all stacks from highest total value to lowest.
4.  Selects the top 5 stacks.
5.  Sums the total value of those 5 stacks.
6.  **Final Range:** Displays `(Total / 2)` to `(Total)`.

## 🛠️ Tech Stack

* HTML5
* CSS3 (Custom variables, Grid layout, Responsive design)
* JavaScript (DOM manipulation, LocalStorage for settings)

---
*Created for the community (ngl this is all ai).*
