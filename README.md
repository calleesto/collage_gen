# Collage Generator in Bash

A modular Bash-based utility for creating image collages via a GUI. Designed for macOS and Linux, it automates image processing using ImageMagick and Zenity.

## 🚀 Features
- **GUI-Driven**: Graphical dialogs for file selection and grid settings via `Zenity`.
- **Interactive Preview**: Generates a temporary HTML gallery to visualize and reorder images by index.
- **System Integration**: Includes custom Unix manual pages and professional signal handling (`trap`) for cleanup.

## 🛠 Dependencies
- **ImageMagick**: Required for `montage` and `convert`.
- **Zenity**: Required for GUI dialogs.
- **Bash 4.0+**

## 📥 Setup & Installation

Clone the repository and make the scripts executable:
```bash
chmod +x main install_man uninstall_man
