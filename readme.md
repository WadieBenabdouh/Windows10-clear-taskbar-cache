# GUIDE

a. Open run command by pressing Windows logo + R keys on the keyboard.

b. Type notepad in the command box and press Enter.

c. Copy the following text onto Notepad:

@echo off

taskkill /f /im explorer.exe

taskkill /f /im shellexperiencehost.exe

timeout /t 3 /NOBREAK > nul

del %localappdata%

\Packages\Microsoft.Windows.ShellExperienceHost_cw5n1h2txyewy\TempState\* /q

timeout /t 2 /NOBREAK > nul

start explorer

@echo on

d. Click on File and Save.

e. Choose a location to save the file on your PC. Enter a “File name” of ClearTileCache.bat and select “Save as type” of All files (*.*).

f. Click on Save.

g. Open File Explorer (Press Windows logo + E keys on the keyboard) and navigate to the location that you chose to save the file to, double click ClearTileCache.bat to run the file.

h. Close the windows after the file is run and check if the changes are effective.