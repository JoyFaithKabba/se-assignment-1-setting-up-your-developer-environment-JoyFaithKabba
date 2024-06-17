
Developer Environment Setup Documentation
Introduction
This document provides a detailed guide on setting up the developer environment for software engineering projects. It includes instructions for installing necessary software and configuring tools.

Operating System Installation
Action: Installed Windows 11
Steps:
Downloaded Windows 11 from the Microsoft website.
Followed the on-screen instructions to complete the installation.
screenshot of windows 11 OS: ![alt text](<Windows_11 installed on my local machine.png>)

IDE Installation
Action: Installed Visual Studio Code
Steps:
Downloaded the installer from the Visual Studio Code website.
Ran the installer and followed the on-screen instructions to complete the installation.
After running the installer, I ran it as an administrator on my local machine
Screenshot: ![alt text](<VS code welcome page on my local machine.png>)
Screenshot:

Version Control System (Git)
Action: Installed and configured Git
Steps:
Downloaded and installed Git from Git's official website.
Created a git account and created a new repository and named it 'Demo'
Git repository link: 
Opened a terminal and configured Git with my github account running the command:
git config --global user.name "JoyFaithKabba"
git config --global user.email "joyah1.kjfk@gmail.com"
Screenshot:![alt text](<Git and github config terminal.png>)
Screenshot:![alt text](<Github account Profile.png>)
Screenshot: ![alt text](<Github first repository.png>)
Github first repository link: https://github.com/JoyFaithKabba/demo.git

Programming Languages and Runtimes
Action: Installed Python
Steps:
Downloaded the installer from the Python website.
Ran the installer and ensured to check the option to add Python to PATH.
Searched for python's default folder after installation
Copied the address
Searched for 'environment variables' in settings and navigate to 'system variables'
Clicked on 'path', clicked on new and pasted the address I copied. 
Clicked 'ok' close all tabs
Screenshot:![alt text](<System variable (path) settings for python.png>)
Screenshot:![alt text](<python in control panel.png>)

Package Managers
Action: Verified pip installation
To verify: Yo can either open comand prompt or Gir bash(always run as administrator) and run a command.
Command:
python v-version
 pip --version
 Screenshot: ![alt text](<Verifying python and pip installation on Git bash.png>)

Database Configuration
Action: Installed MySQL
Steps:
Downloaded the MySQL installer from the MySQL website.
Ran the installer and followed the on-screen instructions to install and configure MySQL.
Followed all instruction on screen to intsall it correctly, created a strong password and configured
Set up environment for 'My SQL' in environment variaoble by adding a new path
After, you can either run My SQl as an administrator and enter your password to have access or run command prompt and run the command: mysql -u root -p, then enter your password
Screenshot:![alt text](<My SQL database in command line client.png>)
Screenshot:![alt text](<My SQL in command prompt.png>)
Screenshot:![alt text](<My SQL environment set up.png>)

Virtualization Tools (Optional)
Action: Installed Docker
Steps:
Downloaded the installer from the Docker website.
Ran the installer and followed the on-screen instructions to complete the installation.
Screenshot: ![alt text](<Docker installation tutorial.png>)
Screenshot: ![alt text](<Docker installation wizard.jpg>)

Extensions and Plugins
Action: Installed necessary extensions in Visual Studio Code
Steps:
Opened Visual Studio Code.
Went to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.
Searched for and installed the following recommended extensions:
Python
pip
git bash and many others
Screenshot: ![alt text](<Visual code  downloaded extensions.png>)

Reflection on Challenges
Challenge: Configuring Git due to a missing path variable.
Solution: Added Git to the system PATH manually by following instructions from the Git documentation.