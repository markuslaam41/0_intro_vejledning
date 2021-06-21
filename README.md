Getting Started Guide

Setup Option-I: For experiments and writing code on the go in browser

The quickest way to get started!
•	Go to https://snack.expo.io  OR https://codesandbox.io/ OR Codepen
– Create a new React Native project or find existing project
●	Change the code in the browser and watch the changes :)

Setup Option-II: Local Environment
Software Requirements

1.	Text Editor
      To write code you can download and install any text editor of your choice. Some of the text editors that can be recommended for the course are:
      o	Sublime Text (http://www.sublimetext.com/)
      o	Atom (https://atom.io/)
      o	Notepad++ (https://notepad-plus-plus.org/downloads/)
      o	Brackets (http://brackets.io/)
      o	Visual Studio Code (https://code.visualstudio.com/)
      o	Code Share (https://codeshare.io/)
      o	Or any text editor you are already familiar with

2.	Browser
      Although you may use any preferred browser, but I recommend using Chrome. Chrome v. 46 or later works fine with HTML5. Not all browsers may support all the HTML5 features therefore in case of other browsers you might encounter problems while solving some of the hands-on exercises. So, to avoid those problems you can use chrome as a browser.

3.	Command Line Tools
      Familiarity with the command-line shell will be essential for the exercises. In Windows a cmd window or power shell with admin privileges would be needed. On a Mac or in Linux, a terminal window can be used.

Downloading and Installing Git
•	To install Git on your computer, go to https://git-scm.com/downloads and download the Git installer for your specific computing platform.
•	Then, follow the installation steps as you install Git using the installer.
•	You can find more details about installing Git at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git. This document lists several ways of installing Git on various platforms.
•	Alternatively, installing some of the GUI tools like GitHub Desktop will also install Git on your computer.
•	On a Mac, setting up XCode command-line tools also will set up Git on your computer.
•	You can choose any of the methods that is most convenient for you.

Some Global Configurations for Git
•	Open a cmd on windows or terminal on your Mac computer.
•	Check to make sure that Git is installed and available on the command line, by typing the following at the command prompt/terminal:
>> git --version

•	To configure your user name to be used by Git, type the following at the prompt:

>> git config --global user.name "Your Name"

•	To configure your email to be used by Git, type the following at the prompt:

>> git config --global user.email <your email address>

•	You can check your default Git global configuration, you can type the following at the prompt:

>> git config --list

Initializing GIT Repository on your Computer

Create a folder react-projects on your computer

Now open your text editor in this folder

Add a file named index.html to this folder, and add the following HTML code to this file:

<!DOCTYPE html>
<html>
    <head></head>

    <body>
        <h1>This is a Header</h1>
	<p>Hello, World! </p>
    </body>
</html>

Initializing the folder as a Git repository

•	Go to the react-projects folder via command prompt/terminal and type the following at the prompt to initialize the folder as a Git repository:

>> git init

The above command will initialize GIT repository.





Some useful Git Commands
Checking your Git repository status

•	Type the following at the prompt to check your Git repository's status:
>> git status

Executing this command will give you information about unstage files

Adding files to the staging area
•	To add files to the staging area of your Git repository, type:
>> git add .

Commiting to the Git repository
•	To commit the current staging area to your Git repository, type:
>> git commit -m "first commit"

Checking the log of Git commits
•	To check the log of the commits to your Git repository, type
>> git log --oneline

For Adding Changes to Remote Repository

Create account on GitHub

Create new repository with the same name as local git repository

Copy url of remote repository

Using command line tools cd to local git repository and then type:

>> git remote add origin <URL of Remote Repository>

This might ask you for your GitHub Username and Password

>> git push -u origin master

Now you can check the remote repository and it will have the same files as your local repository.

Setting up NodeJS

In your browser open a link www.nodejs.org

Scroll a bit down and you will see the NodeJS download buttons for your specific system. Click on the current version of NodeJS

Once the download is completed, double click on the downloaded file to initiate installing NodeJS package on your system.

Follow on screen instructions to successfully install NodeJS.

Once the installation has been finished, go to terminal to verify the installation.

In terminal window type

>> Node -v

OR

>> Node --version

As a result of both commands, in case of successful installation, the version of NodeJS will be displayed on the screen.

Node package automatically installs npm. So you can verify the installation of npm in a similar way.

>> npm -v

OR

>> npm --version 
