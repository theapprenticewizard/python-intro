# Getting Started With Python (Windows)

![Python Logo](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png "The Python Logo")

- [Getting Started With Python (Windows)](#getting-started-with-python-windows)
                - [Who should read this?](#who-should-read-this)
                - [What's Needed](#whats-needed)
    - [Installation](#installation)
        - [1. Download Python](#1-download-python)
        - [1. Add Python to PATH and Install](#1-add-python-to-path-and-install)
        - [3. Open The Command Line](#3-open-the-command-line)
        - [4. Confirm Installation](#4-confirm-installation)
    - [Writing Python](#writing-python)
        - [1. Acquiring a Code Editor](#1-acquiring-a-code-editor)
        - [2. Install Atom](#2-install-atom)
        - [3. Create a Folder to Store Code](#3-create-a-folder-to-store-code)
        - [4. Write Python Code](#4-write-python-code)
        - [5. Run the Code](#5-run-the-code)

Python is a general purpose programming language for building anything imaginable.  It's used in many places including but not limited to Block Chain programming, Machine Learning and Web Developement. And in my opinion, is the best programming language to get started programming with.

##### Who should read this?
People who are the target of this manual have a minumum set of computer skills and an eagerness to get started
with programming.  Anyone with a strong desire to learn should be able to complete these instructions with ease in less than 20 minutes.

##### What's Needed
* Windows Computer
* Internet Connection


## Installation
### 1. Download Python
Go to the python website located [here](https://www.python.org/getit/) and click the download button for the latest version.


![Download Button](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/1.%20Download%20Python.PNG)

### 1. Add Python to PATH and Install
Open the downloaded file and in the first window click the checkbox that says "Add Python 3.7 to PATH".  Once the checkbox has been clicked, click "Install Now" leaving the directory default. And when the setup is completed click the exit button in the bottom left hand corner.


![Add to Path Button](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/2.%20Add%20Python%20to%20Path.PNG)

### 3. Open The Command Line
Press ![windows key](https://i.stack.imgur.com/MB2Nl.jpg) + r to open the the run prompt then type cmd and press enter.

![Run Prompt](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/3.%20Run%20Prompt.PNG)

### 4. Confirm Installation 
In the terminal, enter the command `py --version`.  If the response looks like this then the installation worked. 

![Command Prompt](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/5.%20Check%20Installation.PNG)


## Writing Python

### 1. Acquiring a Code Editor
To create Python programs you must first download and install a code editor. Atom is one of such code editors and you can find it [here](http://atom.io).   When you arrive at the homepage click the download button.

![atom.io homepage](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/1.%20Get%20Atom.PNG)

### 2. Install Atom
Install the Atom code editor by simply double clicking the `.exe` file in the Downloads folder. When opened up it should look like this. 

![installed atom text editor](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/2.%20Install%20Atom%20Code%20Editor.PNG)

### 3. Create a Folder to Store Code
In the home screen of Atom click open a project. In the open folder dialogue navigate to the `Documents` folder right click any directory and hove over `New` then click `Folder`.  Then type in a memorable name and press enter when completed. Finally once you are inside the new folder click `Select Folder` in the bottom right hand corner.

![New Project Screen](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/4.%20Select%20Folder.PNG)

### 4. Write Python Code
Left Click the folder in the top left corner and click `New File`.  In the new file dialogue enter `hello.py`.  Close all the code tabs at the top and enter this one line of code.  `print("Hello, World!")`. The editor should look like this.

![Editor](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/4.%20Code%20Capture.PNG)

### 5. Run the Code
Go to the command prompt and type the command `cd Documents` from there you will type the `cd` command again but this time type in the name of the folder created before.  Use quotes around the folder name if the folder has spaces. E.g. `cd "My First Program"`. Finally, type py `hello.py` to run the code created earlier. The results should look like this.

![Results](https://raw.githubusercontent.com/theapprenticewizard/python-intro/master/images/6.%20completed%20first%20program.PNG)