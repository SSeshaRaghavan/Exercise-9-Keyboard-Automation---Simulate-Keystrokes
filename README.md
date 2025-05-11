# Exercise-9-Keyboard-Automation---Simulate-Keystrokes
~~~
Name : W Allen Johnston Ozario  
Reg.No : 21222411004  
~~~

## Aim
To create a UiPath workflow that opens Notepad and simulates keyboard typing and shortcuts like saving a file using simulated keystrokes.

## Materials Required
UiPath Studio (Community or Enterprise Edition)

Windows OS

Notepad (built-in Windows app)

Basic knowledge of keyboard automation using UiPath

## Procedure
Step 1: Create a New Process
Open UiPath Studio and create a new process named KeyboardAutomation.

Step 2: Open Notepad
Drag and drop Start Process activity.

Set the properties:

FileName: "notepad.exe"

Step 3: Add Delay (Optional but Recommended)
Add a Delay activity to wait for Notepad to open.

Duration: 00:00:02 (2 seconds)

Step 4: Use Type Into Activity
Drag and drop a Type Into activity.

Click Indicate on Screen and select the Notepad window.

Text to type:
~~~
Hello! This text is typed by UiPath using keyboard automation.
💡 Enable ClickBeforeTyping and Activate options in the Properties panel for accuracy.
~~~
Step 5: Use Keyboard Shortcuts (e.g., Save)
Drag and drop a Send Hotkey activity.
Indicate the same Notepad window.
Set the key to Ctrl + S (hold Ctrl, then choose S).

Step 6: Type File Name and Press Enter
Add a Type Into activity to type file name (e.g., MyFile.txt).
Add another Send Hotkey for pressing Enter.

## OUTPUT:
Notepad will open.
Text will be typed automatically.
Ctrl + S will be triggered to save.
The file will be saved with the name MyFile.txt.

![Screenshot 2025-05-11 220557](https://github.com/user-attachments/assets/b6d3cf6e-ec49-47eb-83eb-b50e666a7af5)

![Screenshot 2025-05-11 220605](https://github.com/user-attachments/assets/db69d067-48c9-4651-ae83-ea71c10c9395)

![Screenshot 2025-05-11 220620](https://github.com/user-attachments/assets/ca8c8277-4897-45a9-b550-f4f3ab167d42)

![Screenshot 2025-05-11 220541](https://github.com/user-attachments/assets/c8f75b1d-d6bb-4476-b6e6-32cd650d7515)

## Result:
The workflow successfully simulates human-like typing in Notepad and saves the file using keyboard shortcuts through UiPath's keyboard automation capabilities.

