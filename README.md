# C-Keylogger
A keylogger made using C++ of windows.

# Features (for now):
- Logs keystrokes to keys.txt
- Uses windows API LowLevelKeyboardProc to capture keystrokes

# TODO:
- Send the keystrokes to a remote server
- Make a separate server to see the keystrokes in a gui
- Make it stealthy
- Make the keystrokes more understandable
- Send the window application name being used to the server
- Encrypted communication with the server
- Think more ideas

# References:
- https://learn.microsoft.com/en-us/previous-versions/windows/desktop/legacy/ms644985(v=vs.85)
- https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowshookexa
- https://learn.microsoft.com/en-us/windows/win32/api/winuser/ns-winuser-kbdllhookstruct?redirectedfrom=MSDN
- https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes
- https://github.com/awakecoding/Win32Keyboard/tree/master

Used CLion to develop this project.
