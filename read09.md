# Text Editor
*_A text editor is a piece of software that you download and install onyour computer, or you access online through your web browser, thatallows you to write and manage text, especially the text that you writeto build a web site. The text editor has to be one of the mostimportant tools you can use as an aspiring web developer._*
![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQ4Q2E63VRWgzzHini2FL0fFKH4w-pKWGAuQ&usqp=CAU)
# The Command Line (Linux)
** A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text**.
The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands
* *_Opening a Terminal_*
1. If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.
2. If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.
3. If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is Putty (free) .
* *_The Shell, Bash_*
Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. This tutorial will assume you are using bash as your shell.

If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages
* *_Shortcuts_*
Here's your first shortcut. When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys. So don't bother re-typing out commands you have previously entered, you can usually just hit the up arrow a few times. You can also edit these commands using the left and right arrow keys to move the cursor where you want
# Basic Navigation(Linux)
In this section, we'll learn the basics of moving around the system. Many tasks rely on being able to get to, or reference the correct location in the system. As such, this stuff really forms the foundation of being able to work effectively in Linux. Make sure you understand it well0.
so lets chicke some commands:
1. **pwd**
The first command we are going to learn is pwd which stands for Print Working Directory. (You'll find that a lot of commands in linux are named as an abbreviation of a word or words describing them. This makes it easier to remember them.) The command does just that.
2. **ls [options] [location]**
It's one thing to know where we are. Next we'll want to know what is there. The command for this task is ls. It's short for list. Let's give it a go.
3. **cd [location]**
In order to move around in the system we use a command called cd which stands for change directory.

**Let's start by getting familiar with moving around. Use the commands cd and ls to explore what directories are on your system and what's in them. Make sure you use a variety of relative and absolute paths. Some interesting places to look at are**:
* /etc - Stores config files for the system.
* /var/log - Stores log files for various system programs. (You may not have permission to look at everything in this directory. Don't let that stop you exploring though. A few error messages never hurt anyone.)
* /bin - The location of several commonly used programs (some of which we will learn about in the rest of this tutorial.
* /usr/bin - Another location for programs on the system.
# More About Files in linux
After the previous section I'm sure you're keen and eager to get stuck into some more commands and start doing some actual playing about with the system. We will get to that shortly but first we need to cover some theory so that when we do start playing with the system you can fully understand why it is behaving the way it is and how you can take the commands you learn even further. That is what this section and the next intend to do. After that it will start getting interesting, I promis
** *_Everything is a file under Linux
Even directories.
Linux is an extensionless system
Files can have any extension they like or none at all.
Linux is case sensitive
Beware of silly typos._* **
* **file**
obtain information about what type of file a file or directory is.
* **ls -a**
List the contents of a directory, including hidden files.
