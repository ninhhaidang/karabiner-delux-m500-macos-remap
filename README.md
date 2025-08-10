# Karabiner Delux M500 macOS Remap

This repository contains a Karabiner-Elements configuration file that remaps the **forward** and **backward** buttons on the Delux M500 mouse to **Command+C** (Copy) and **Command+V** (Paste) on macOS.

## 🎯 Features
- **Button5 → Command+C**
- **Button4 → Command+V**
- Works on macOS with [Karabiner-Elements](https://karabiner-elements.pqrs.org/)

## 📥 Installation
1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/).
2. Download the configuration file from this repository:
   ```bash
   curl -O https://raw.githubusercontent.com/ninhhaidang/karabiner-delux-m500-macos-remap/main/config.json
3. Copy the file into Karabiner's complex_modifications folder:
   ```bash
   mkdir -p ~/.config/karabiner/assets/complex_modifications
   cp config.json ~/.config/karabiner/assets/complex_modifications/
4. Open Karabiner-Elements → Complex Modifications → Add Rule → enable Map Mouse Buttons to Copy/Paste.

## 🖱 Device
- **Mouse**: Delux M500
- 
- **Platform**: macOS
- **Software**: Karabiner-Elements

## 📜 License
This project is released under the [MIT License](LICENSE).
