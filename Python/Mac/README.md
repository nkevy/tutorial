Python Tutorial for Mac
=======================
Author: nkevy

The following tutorial is intended to help Macintosh users install the Python Programming language. After the tutorial you should be able to open a terminal session and type python or python3 and run the python command line tool.

Step 1. Check the Preinstalled Python
-------------------------------------
1. Open the terminal app, this is called a terminal session, press cmd+space then type: Terminal
2. Press enter.
3. type: python
4. Press enter.
5. You should see >>> preceding the cursor if your Macintosh is setup correctly you should also see Python 2.7 or another version number.
6. Note the version number, often this number is 2.7.XX as Python is preinstalled on Macintosh.

Step 2. Install Python
----------------------
1. Navigate to https://www.python.org/downloads/mac-osx/
2. Find the Stable Releases section.
3. Click and download the latest macOS 64-bit installer.
4. Open a Finder window.
5. Navigate to Downloads.
6. Double click on the python-X.X.X-macosxXX.X.pkg
7. Follow instructions presented by the installer and enter your password when prompted.
8. Another Finder window will open at the end of the Install Python setup find the Install Certificates.command
9. Double click: the Install Certificates.command, a terminal session will open and the command will execute and let the process finish.
10. In new Finder window double click: Update Shell Profile.command 
11. Open a new terminal session.
12. Type: pythonX where X is the first number of the python version number that you dowloaded. For example type: python3
13. If you see >>> preceding the cursor and the pythonX.X.XX that you dowloaded then you are done. If not please continue.

Step 3. Add Python to your PATH
-------------------------------
1. Open a terminal session and type: nano .bash_profile
2. Press enter.
3. Don't panic.
3. Navigate to the bottom of page by pressing the down arrow
4. Press enter to create a new line.
5. Remember X represents the version number of the python you downloaded, type: PATH="/Library/Frameworks/Python.framework/Versions/X.X/bin:${PATH}" 
6. Press enter to create a new line.
7. Type: export PATH
8. Press ctrl+x
9. Press y
10. Press enter
11. To test the changes open a new terminal session.
12. Remember X represents the python version number (here only the fist number, for example python3) Type: pythonX
13. Press enter 
14. You should see the >>> preceding the cursor, if so you are done. If not google: adding python to .bash_profile PATH, it is likely that your python installed to a different location. 


