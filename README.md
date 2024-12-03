# User Account Control (UAC).bat

## Description
This batch script allows you to bypass the User Account Control (UAC) prompt when running programs. It enables you to run programs as if they were invoked by a standard user, without requiring administrator privileges. The script is designed to be drag-and-drop, where you can simply drag any executable or shortcut onto the `.bat` file to run it without administrative elevation.

## How It Works
- The script uses the `set __COMPAT_LAYER=RUNASINVOKER` command to run the program in a manner that simulates being launched without elevated privileges.
- It does not modify any registry keys, unlike other methods that alter the system settings.
- By using the `cmd /min /C`, the script runs in minimized mode, so it does not clutter your workspace.

## Usage
1. Download or save the `User Account Control (UAC).bat` file.
2. Drag and drop any executable (e.g., `.exe`, `.bat`) onto the script.
3. The program will run without the UAC prompt and without requiring admin rights.

## Notes
- This method does not require administrative privileges, and it avoids cluttering the context menu like registry-based solutions.
- It is a safer and simpler alternative to modifying system settings.

## Disclaimer
This script is intended for users who want to avoid the UAC prompt for non-administrative tasks. Use at your own risk. It is always advisable to run programs with appropriate privileges to ensure the security of your system.
