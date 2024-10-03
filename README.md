# Ethical Keylogger Demonstration

---

## Description

The **Ethical Keylogger Demonstration** is a payload designed to showcase how a basic keylogger can capture keystrokes on a Linux machine. This payload is intended for educational purposes, to demonstrate the risks of keylogging and the importance of security measures to prevent unauthorized access. The keylogger records all keystrokes during its runtime and saves the log file for later review.

## How it Works

1. The payload launches a terminal session on a Linux machine.
2. It installs the `logkeys` keylogger, if it’s not already installed.
3. The keylogger is then started, capturing all keystrokes and saving them to a log file.
4. After a set period, the keylogger is stopped.
5. The captured keystrokes are saved to the Bash Bunny’s storage for analysis.

## Requirements

- Target: Linux machine with internet access to install `logkeys`
- Bash Bunny in HID and storage mode

## Ethical Use Disclaimer

This payload is intended strictly for educational purposes and ethical hacking in a controlled environment. Unauthorized keylogging is illegal and unethical. Always ensure you have explicit permission before using this payload.

## Liability Disclaimer

The author of this payload assumes no responsibility for any illegal or unethical use of the code. This payload is provided as-is, and it is the user's responsibility to ensure its use complies with all applicable laws and regulations.

## Usage

1. Insert the Bash Bunny into the target machine.
2. The payload will install and activate the keylogger, capturing keystrokes.
3. After a predetermined time, the log file will be saved to `/keylog.txt` on the Bash Bunny’s storage.
4. Eject the Bash Bunny and review the log file.
