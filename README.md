
Project Scripts Documentation

This project contains three different utility scripts: two batch (.bat) files and one VBScript (.vbs) file. Each serves a different purpose, described below.

Files

1. keyboard.vbs
- Type: VBScript
- Purpose: 
  Simulates or interacts with keyboard input on the system.
- Details:
  - Might simulate keypresses.
  - Typically used to automate tasks that require keyboard interaction without user input.
  - Requires Windows Script Host to run.

2. random.bat
- Type: Batch File
- Purpose: 
  Executes commands randomly or generates random behaviors.
- Details:
  - Likely uses the %RANDOM% variable available in the Windows Command Prompt.
  - Useful for generating unpredictable outputs or for testing random scenarios.

3. terminal.bat
- Type: Batch File
- Purpose: 
  Opens a terminal or runs a series of terminal/command prompt commands.
- Details:
  - May configure or launch a customized terminal environment.
  - Could run scripts or commands automatically on launch.

How to Use

1. VBScript File (keyboard.vbs)
   - Double-click to execute.
   - Alternatively, run from the command line with:
   
         cscript keyboard.vbs
2. Batch Files (random.bat and terminal.bat)
   - Simply double-click to run.
   - Or execute from Command Prompt:

         random.bat
         terminal.bat
Notes

- These scripts are intended for Windows operating systems.
- Some scripts may require administrative privileges depending on the actions performed.
- Always review the scripts before running them to ensure they match your expectations.
