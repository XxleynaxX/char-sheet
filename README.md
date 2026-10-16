# 🛡️ Chronicles – Digital Character Sheet

A modern, web-based character sheet specifically designed for roleplay projects and servers (such as Conan Exiles). This web app allows players to create detailed characters, save them locally, export/import them via JSON, and download the entire character sheet directly as a polished PNG image.

---

## ✨ Features

- **👤 General Info & Races:** Comprehensive race and subrace selection with automatic height verification (including warning and confirmation popups for deviations).
- **✨ Magic & Rules:** Optional magic proficiency with element selection, sources, and side effects, including mandatory confirmation of server magic rules via a modal popup.
- **🛠️ Professions & Crafting:** Selection of main and secondary professions with detailed descriptions.
- **👁️ Appearance & Features:** Dedicated fields for hair, eye color, and individual build/distinct feature descriptions.
- **⚖️ Alignment & Moral:** Character alignment classification from "Very Good" to "Evil".
- **🔒 OOC Safety Info:** Integrated OOC consent for restraints & enslavement as well as real-life phobias/boundaries to protect players.
- **💾 JSON Import & Export:** Save and load complete character files as well as automatic browser local storage backup (`LocalStorage`).
- **🖼️ Direct Image Export:** Automatically generates a sharp PNG screenshot of the complete character sheet in a sleek dark fantasy design using `html2canvas`.

---

## 🚀 Quick Start & Usage

Since this is a pure **single-file web application** (HTML with embedded CSS & JavaScript), you don't need any server or Node.js dependencies!

1. Download the `.html` file (or clone the repository).
2. Simply open the file with a double-click in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Fill out your character sheet and click **"Complete character & save as image"**.

---

## 📦 Project Structure

```text
├── Char Bogen_56.html    # Core application: Combines HTML structure, responsive dark-fantasy CSS styling, and complete JavaScript control (JSON export, LocalStorage, html2canvas image generation)
└── README.md     # Project documentation and guide
