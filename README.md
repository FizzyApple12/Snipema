# Snipema
"Web Scrapers are so... unisex."

Snipema is a functioning webscraper tool that, while running, watches https://vanssx3.github.io/Snipema for when Mr. York's autograph is available for purchase. Currently, when the autograph is available, the program will only open the login page, but soon it will be able to automate the full process of purchasing the product.

Snipema is currently compattable with Windows and Linux operating systems.

# Dependencies
In order to run the program as intended, python-3, colorama, and urllib3 need to be installed.

# Python-3 Installation

For Windows Users, download it here: https://www.python.org/downloads/windows/

For MacOS Users, download it here: https://www.python.org/downloads/macos/

For Ubuntu/Debian based Linux Distros, run
```sh
sudo apt-get install python3
```

For Arch based Linux Distros, run
```sh
sudo pacman -S python3
```

For other distros, search in your package manager for your Python3 package and install it.

# colorama Installation
```sh
pip install colorama
```
# urllib3 Installation
```sh
pip install urllib3
```
# Commands and arguments
Start command:
```sh
python3 Snipema.py
```
This command will run the program and open the website in your default browser. If no default browser is selected, the program may fail to function.

Custom Arguments:
```sh
python3 Snipema.py -c
```
-c opens the website in Google Chrome

```sh
python3 Snipema.py -f
```
-f opens the website in Firefox

```sh
python3 Snipema.py -e
```
-e opens the website in Microsoft Edge

