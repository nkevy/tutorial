Python Tutorial for Linux
==========================
Author: nkevy

The following tutorial is intended to help Linux users install the Python Programming language. After the tutorial you should be able to open a terminal session and type python or python3 and run the python command line tool.

Step 1: Update the Package Manager
----------------------------------
1. Open a terminal window, press: ctr+alt+t or right click and select open terminal or enter the Activities launcher and type: terminal.
2. Click the terminal window.
3. Type: sudo apt-get update
4. Press enter.
5. Enter the password for your user account. 
6. Press enter. 
7. Wait until the process completes. 
8. Type: sudo apt-get upgrade
9. Press enter
10. If prompted, enter the password for your user account. 
11. Press enter. 
12. Wait until the process completes.
13. Type: sudo apt-get install python3
14. Press enter. 
14. If prompted, enter the password for your user account. 
15. Press enter. 
16. Wait until the process completes
17. Type: python3
18. If you see the python version number printed and >>> preceding the cursor, your done. 
19. To close python, type: exit()
20. Press enter. 

If sudo apt-get update Or install python3 Prints an Error:
----------------------------------------------------------
1. Check that your user has root permission. Type: sudo su
2. Type the password for your user account.
3. If the command executes without error you have root permission.
4. If not, google: give linux user account admin rights 
5. To exit sudo su type: exit
6. Press enter. 
7. It is likely that you are using a distribution of linux that cannot find a repositry that contains python3. Please see: https://docs.python-guide.org/starting/install3/linux/
9. Find a repository that contains a python build compatable with your linux version. (The link suggests deadsnakes PPA see: https://launchpad.net/~deadsnakes/+archive/ubuntu/ppa).
8. To install a repository type: sudo add-apt-repository ppa:<the new repository>
9. Press enter and wait. 
10. Type sudo apt-get update
11. Press enter and wait.
12. Type: sudo apt-get install python3
13. Press enter.
14. If the above install command fails, search for another package manager. 15. Google: <my linux distribution> package manager
16. Update the package manager.
17. Install python3 with that package manager. 

Add Python To PATH:
---------------------
1. To run a python session from any directory add python to your environment variable called PATH.
2. Type: cd $HOME
3. Press enter. 
4. Type: nano .bashrc
5. Press enter. 
6. Scroll down by pressing the down arrow. 
7. Look at lines that contain PATH=
8. Check to see if the location of python3 is already added to your PATH. If so your done, type: ctrl+x
9. Create a new line at the bottom of the page, scroll to the last line and press enter. 
10. Type: export PATH=<location of python3>:$PATH
10.1 For example,  PATH=/usr/bin/python:$PATH
11. Press ctrl+x
12. Press y
13. Close and reopen the terminal. 
