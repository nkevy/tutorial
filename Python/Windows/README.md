Windows setup for Python
========================
Author: nkevy

Step 1 Dowload Python
---------------------
1. Navigate to https://www.python.org/downloads/windows/
2. Find the Stable Relaeses section
3. Determine if you have a 64 or 86 bit Windows
3. Click and dowload the Windows x86-64 executable installer (64 bit) or the Windows x86 executable installer (86 bit)

Step 2 Install Python
----------------------
1. Navigate to your Dowloads folder in Windows File Explorer
2. Double click on the python-x.x.x-amd64.exe (the x.x.x will be replaced withe version number of Python, dont worry about it)
3. An install Python setup window will appear 
4. Click the check box at the bottom of the page that says Add Python x.x to PATH
5. Select Install Now
6. User Account Control may appear if so select Yes
7. On the Setup was successfull page, select Disable path length limit
8. User Account Control may appear if so select Yes
9. On the Setup was successfull page, select Close

Step 3 Test Python
------------------
1. Press or click the windows button
2. Type cmd, you should see the Command Prompt App
3. Press enter, click Open or click Run as administrator 
4. User Account Control may appear if so select Yes
5. type: python
6. press enter, text stating the Python vertion should appear. If so python was installed corectly if not google: python windows not working
7. to exit type: exit()
8. press enter, you should no loger see the >>> before the cursor 
Your Done! If you need to learn about the PATH see bellow.

Add Python to PATH
------------------
If you forgot or chose not to select the Add Python x.x to PATH follow these steps.
1. Find the Python x.x exicutable, usualy in C:\Users\exampleuser\AppData\Local\Programs\Python\PythonXX\python.exe (the XX stands for version number)
2. Once you find the python.exe copy the path or location (you can right click on the python.exe and copy the text after the Location: feild or copy thetext in the top bar of windows File Explorer)
3. Open Windows Control Panel, click or press the windows key and type: control panel
4. In the search box (top right) type: environment variables
5. You should see the System option, select System
6. Select Advanced system settings, the System Properties window should appear 
7. Select Environment Variables... (bottom right), the Environment Variables windows should appear
8. Select Path in the User variables for exapmleuser window (should be blue)
9. Select Edit... , the Edit environment variable windows should appear
10. Select New (top right)
11. Paste into the new box, or type ctrl+v
12. Select OK (bottom right Edit environment variable)
13. Select OK (bottom right Environment Variables)
14. Select OK (bottom right System Properties)
15. Your done, close all windows and test by running Python in any directory location
