

# my-notes
>Today we start



![rocet](https://i.gifer.com/D4a.gif)

# Termial command line 




Once upon a time, in a land of computers and operating systems, there was a magical tool called **the Terminal Command Line**. This tool allowed the people of the land to interact with their computers in a powerful and direct way.

To use this tool, the people would open a window on their computer called a terminal, and start typing commands into it. These commands would **tell the computer what to do**, and the computer would respond by carrying out the task.
![termial](https://w7.pngwing.com/pngs/247/392/png-transparent-computer-terminal-gnome-terminal-computer-icons-terminal-emulator-gnome-template-electronics-cartoon.png)

* * * * * * * * * * * * * * * * * * *
Some basic commands are:

*               ls                   *
 list all the files and directories in the current folder      
*             pwd                     *
displays the file path from the root directory to the current working directory
*             mkdir                  *
make a new directory in the filesystem according to its argument
*             cd                       *
used to move throughout the filesystem of a computer. 
*             touch                   *
reates a new file in the current working directory with the name provided.
*             cp                   *
used to copy files or directories.
* * * * * * * * * * * * * * * * * * *

But the people had to be __careful with the Terminal Command Line__, for it was a powerful tool that could cause great harm if used incorrectly. They had to remember to type each command carefully, and to always double-check before deleting files or making other important changes.

Despite the dangers, the Terminal Command Line was a beloved tool among the people of the land, for it gave them great power over their computers and allowed them to accomplish tasks that would have been impossible otherwise. And so they continued to use it, honing their skills and exploring the depths of its power, for many years to come.


***
## Version control System

##### Imagine this scenario

|  Version  |Day |Status    |
|-----|---------|---------|
|Version1	|`1` |ok     |
|Version2  |`2` |ok   |
|Version3   |`3`|error code destroyed|

VCS can be a solution to many problems related to software development, especially when working on projects collaboratively or when managing complex codebases. VCS allows multiple developers to work on the same codebase simultaneously, keep track of changes and revisions, and easily revert to previous versions if necessary.

---

```mermaid
graph LR
A[Working area] -->|git add| B[Steging area]
B -->|git Commit| C{local Repo}
C -->|git push| D[Remote Repo]

ACP Cycle


