Keyboard Event Logger

This Python script uses the pynput library to log keyboard events. When executed, it captures all keystrokes and records them into a file named "keyfile.txt".
Features

    Keystroke Logging: Captures and logs every keystroke.
    Console Output: Prints the captured keys to the console for real-time monitoring.

Requirements

To run this script, you need Python installed on your system along with the pynput library. To install pynput, run:

pip install pynput

Usage

Run the script using Python:

python main.py

Once the script is running, it will log all keystrokes until it is manually stopped. The keys are stored both on the console and in "keyfile.txt".
Important Notes

    Security Considerations: This script logs all keystrokes, which may include sensitive information like passwords and personal data. Ensure that it is used ethically and legally.
    Stopping the Script: To stop the script, focus on the terminal where the script is running and press Ctrl + C or close the terminal window.
    File Output: The "keyfile.txt" is appended each time the script runs. If you want to start a fresh log, delete or rename the existing "keyfile.txt" before running the script again.

Disclaimer

This script is for educational purposes only. The author is not responsible for any misuse or damage caused by this script.
