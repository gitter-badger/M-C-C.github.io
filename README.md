#Glixer - GitHub Pages, Gulp, Jekyll, SCSS, Bootstrap. 

[![Join the chat at https://gitter.im/M-C-C-github-io/Lobby](https://badges.gitter.im/M-C-C-github-io/Lobby.svg)](https://gitter.im/M-C-C-github-io/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Blog, Portfolio & Website build system.

## Why?
1. EASY to use and Quick to get started.
2. Nothing else does this.

People new to web developement and working professionals often do not have the knowledge or time to know which tools they should be using or the know-how to configure them.

This project is meant to be a jump start for people in both groups. 

## Demo
View this jekyll theme in action [here](https://m-c-c.github.io/)

## Built with:
- [Bootstrap](http://getbootstrap.com/)
- [Bourbon](http://bourbon.io/)
- [Browser Sync](https://browsersync.io/)
- [Font Awesome](http://fontawesome.io/)
- [GitHub Pages](https://pages.github.com/)
- [Gulp](http://gulpjs.com/)
- [Jekyll](https://jekyllrb.com/)
- [jQuery](https://jquery.com/)
- [Node.js](https://nodejs.org/)
- [SASS](http://gulpjs.com/)

The tools listed above are included with this package and are ready to go once this package is installed.

## Getting Started
You have options here.  You can either locally develop in which case follow the instructions below for your OS, or you can develop online at [c9.io](https://c9.io).

#### Download and Install the following items:
1. [Ruby Installer](https://rubyinstaller.org/downloads/)
1. Ruby Dev Kit
Make sure to check the 3 boxes BEFORE clicking the INSTALL button.
2. [Node.js](https://nodejs.org/)
3. [Jekyll](https://jekyllrb.com/)
4. Bundler

#### Command Line
- PRESS & HOLD the Windows Key on your keyboard and PRESS R on your keyboard.
This will launch the run window. Type cmd in the box and PRESS ENTER.

Now that you have terminal / command line open, follow the steps below:

1. Clone respository: copy this line `git clone https://github.com/Boardley/boardley.github.io.git`
In your terminal / command line widnow right click and select PASTE.
Once you see the code in the window, PRESS ENTER.
2. Change Directory: After the project is done downloading, type 

3. Type `sudo npm install` PRESS ENTER. 
You might be prompted for your password. Please enter it now.
This will install all of the items necessary for your build system to run. 
Once everything is done installing, move on to the next step.

### C9
1. Logon to Github
2. Fork this [repository](https://github.com/M-C-C/M-C-C.github.io)
3. Copy your fork url e.g. `git@github.com:YOURUSERNAME/M-C-C.github.io.git`
4. On [c9.io)[https://c9.io] create a new workspace
   * Template: Blank (Ubuntu Logo)
   * Clone from Git: use your fork url here
5. See Linux Install Instructions

### Linux install instructions (For distributions with apt-get)
1. Open a BASH terminal and navigate to the project folder. 
2. Enter the Following commands (1 command per line):
```
make
gulp serve
```
### Windows Install

1. Open an Elevated Powershell prompt (You can do this by searching for a progam called PowerShel, Right-Clicking it amd, click Run As Administrator, This won't work without it)
2. Enter the following commands (1 command per line):
```
  SetExecutionPolicy Unrestricted   // You might want to run SetExecutionPolicy AllSigned when finished
  Install-PackageProvider chocolatey
  Install-Package ruby ruby.devkit nodejs git
  gem install jekyll bundler
  npm install -g gulp
  git clone https://github.com/m-c-c/m-c-c.github.io/ // or your forked repo
  cd m-c-c.github.io // Or your forked repo
  bundler update
  bundler install
  npm install
  npm rebuild node-sass
```
## Operation
1. Navigate to the project folder using the Terminal, Command Prompt or, PowerShell and run `gulp serve`
2. Open a web browser if it didn't automatically and go to the following url `http://localhost:8080`
3. Make some changes to the files inside the `_layouts` folder and see it automatically show up! 
4. When you are finished, go back to the command line and terminate the task by `Ctrl-C`

## Built by
[Mike Boardley](https://www.linkedin.com/in/boardley/)

Please email me your comments & feedback.

- by <a href="https://twitter.com/mikeboardley">twitter</a>
- mail <a href="mailto:boardley@gmail.com">boardley[at]gmail.com</a>
- via <a href="https://www.linkedin.com/in/boardley/">LinkedIn</a>

=========

