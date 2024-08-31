Locally stored Keylogger

This Python code logs keystrokes and associates them with the currently active window. The keylogger records typed text, while tracking window changes to ensure logs are segmented by active windows. The script periodically logs typed text if there are no window changes within a defined interval. The keylogger stores the keyfile locally on the target system.

Dependencies:

pynput
pygetwindow

You can run the following command in Command Prompt to install the dependencies:

pip install pynput pygetwindow

How to run it:

python keylogger.py

