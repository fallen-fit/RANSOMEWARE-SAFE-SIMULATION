# Ransomware Simulation

**Project:** Educational ransomware attack simulation for cybersecurity awareness.

## Overview

This Python script simulates ransomware behavior by encrypting a folder named `work secrets`, locking the screen with a red GUI, displaying a ransom note with a fake Bitcoin address, and enforcing a timer countdown. The user must enter the correct PIN to decrypt and unlock the system. Incorrect PIN entries reduce the available time, and if time runs out, the folder is deleted.

## Features

- AES encryption with Fernet symmetric key
- Fullscreen red GUI blocking user input
- Ransom note with fake Bitcoin address
- 4-hour countdown timer with hour deductions on wrong PINs
- Folder deletion after timer expires
- PIN code: `1234`

## How to Use

Prepare folder:

Create a folder named work secrets {or a name of your choice} in the same directory and put files you want to simulate encrypting.

Run the script:

bash

python gameapp.py
Compile to EXE (optional):

Use PyInstaller to create a Windows executable:

bash

pyinstaller --onefile --noconsole gameapp.py
Disclaimer
For educational use only. Do not run on systems or data without permission.

