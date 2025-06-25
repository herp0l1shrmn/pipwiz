pipwiz: Python Package Management Wizard
[![PyPI version](https://badge.fury.io/py beginner-friendly, cross-platform GUI wizard for installing, upgrading, and uninstalling Python packages using pip.
Built with PyQt5. No command-line knowledge required!

Features
Modern, intuitive wizard interface (Windows-style)

Install, upgrade, or uninstall any Python package

Real-time pip output in a friendly GUI

Custom confirmation for uninstalling pipwiz itself

Automatic detection if a package is already installed

Beautiful banner and app icon

One-file, easy to use and distribute

Installation
bash
pip install pipwiz
Usage
Just run:

bash
pipwiz
Or, if you installed from source:

bash
python -m pipwiz.main
Screenshots
![pipwiz screenshot](https://raw.githubusercontent.com/herp0l1shrmn/pipwiz/main your screenshot here!)*

How It Works
Welcome:
Start the wizard and get a friendly introduction.

Package Selection:
Enter the name of the package you want to manage.

Status & Actions:

If the package is not installed: Install it with one click.

If the package is already installed: Upgrade, Uninstall, or leave as is.

For pipwiz itself, a special confirmation is shown before uninstall.

Real-Time Output:
See pip’s output in real time, including errors and success messages.

Uninstalling pipwiz
If you try to uninstall pipwiz using the wizard, you’ll get a confirmation dialog to prevent accidental removal.
You can always reinstall it with:

bash
pip install pipwiz
Requirements
Python 3.7 or newer

PyQt5

Contributing
Contributions, issues, and feature requests are welcome!
Open an issue or pull request on GitHub.

License
MIT License

Author
herp0l1shrmn or hrmnpy

GitHub

PyPI

Enjoy easy Python package management with pipwiz!
