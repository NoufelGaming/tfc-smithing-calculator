# 🔨 TerraFirmaCraft Smithing Calculator

A simple, web-based calculator to help TerraFirmaCraft players achieve "Perfectly Forged" items by guiding them through the precise anvil hit sequences.

---

## ✨ Features

* Calculates the exact sequence of anvil presses needed.
* Accounts for current green arrow position, red arrow target, and specific final required hits.
* Considers all available anvil buttons for optimal pathfinding.
* Easy to use web interface.

---

## 🚀 How to Use

1.  **Open the Calculator:** Visit the live calculator [here](https://noufelgaming.github.io/tfc-smithing-calculator/)
2.  **Input Current Green Arrow Position:** Enter the numerical value where your green arrow is currently located on the smithing bar.
3.  **Input Red Arrow (Final Target) Position:** Enter the numerical value where the red arrow is pointing. This is your ultimate goal.
4.  **Input Required Final Hits:** Look at the red-bordered slots at the top of your anvil interface. Enter the *numerical value* for each of these hits, starting from the **rightmost** red slot, then the middle, then the leftmost. Separate each number with a comma (e.g., `-15, 2, 7` for three hits, or `16, 2` for two hits).
5.  **Input All Available Anvil Buttons:** List *all* the numerical values of the buttons you can press on your anvil, separated by commas (e.g., `2, 7, 13, 16, -3, -6, -9, -15`). (These are the defaults)
6.  **Click "Calculate Steps":** The calculator will display the precise sequence of button presses you need to make in two phases:
    * **Phase 1:** Intermediate presses to get your green arrow to the correct "pre-final" position.
    * **Phase 2:** The final required presses as dictated by the red-bordered slots, in the correct order.

---

## 🛠️ Development & Contribution

This calculator is built with HTML, CSS (TailwindCSS), and JavaScript.

If you'd like to contribute or improve this calculator:
1.  Fork this repository.
2.  Clone your forked repository: `git clone https://github.com/YOUR_USERNAME/tfc-smithing-calculator.git`
3.  Make your changes.
4.  Commit your changes and push to your fork.
5.  Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
