# Locally stored Keylogger
This Python code logs keystrokes and associates them with the currently active window. The keylogger records typed text, while tracking window changes to ensure logs are segmented by active windows. The script periodically logs typed text if there are no window changes within a defined interval. The keylogger stores the keyfile locally on the target system.

## Dependencies:
1. pynput
2. pygetwindow

You can run the following command in Command Prompt to install the dependencies:
``` bash
pip install pynput pygetwindow
```
## How to run it:
``` bash
python keylogger.py
```
## Caveats:
This code can easily be identified as a malicious code by the Windows Defender

Disclaimer: This program is meant for educational purposes only
