# pipwiz: Python Package Management Wizard

A beginner-friendly, cross-platform GUI wizard for installing, upgrading, and uninstalling Python packages using pip.  
Built with PyQt5. No command-line knowledge required!

---

## Features

- Modern, intuitive wizard interface (Windows-style)
- Install, upgrade, or uninstall any Python package
- Real-time pip output in a friendly GUI
- Custom confirmation for uninstalling pipwiz itself
- Automatic detection if a package is already installed
- Beautiful banner and app icon
- One-file, easy to use and distribute

---

## Installation

pip install pipwiz

---

## Usage

Just run:

pipwiz

Or, if you installed from source:

python -m pipwiz.main

---

## How It Works

1. **Welcome:**  
   Start the wizard and get a friendly introduction.

2. **Package Selection:**  
   Enter the name of the package you want to manage.

3. **Status & Actions:**  
   - If the package is **not installed**: Install it with one click.
   - If the package is **already installed**: Upgrade, Uninstall, or leave as is.
   - For pipwiz itself, a special confirmation is shown before uninstall.

4. **Real-Time Output:**  
   See pip’s output in real time, including errors and success messages.

---

## Uninstalling pipwiz

If you try to uninstall pipwiz using the wizard, you’ll get a confirmation dialog to prevent accidental removal.  
You can always reinstall it with:

pip install pipwiz

---

## Requirements

- Python 3.7 or newer
- PyQt5

---

## Contributing

Contributions, issues, and feature requests are welcome!  
Open an issue or pull request on [GitHub](https://github.com/herp0l1shrmn/pipwiz).

---

## License

MIT License

---

## Author

**herp0l1shrmn or hrmnpy**  
- [GitHub](https://github.com/herp0l1shrmn)
- [PyPI](https://pypi.org/user/hrmnpy/)

---

**Enjoy easy Python package management with pipwiz!**
