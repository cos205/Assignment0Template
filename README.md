# COS205 Assignment 0

The only purpose of this assignment is to practice submitting files through github classroom.
All you have to do is add a file at the root directory with your name, NetId, and Princeton email, and push to github.

## Shell

If you are using a windows machine, you may need to download tools that enable a unix-style shell such as [cygwin](https://www.cygwin.com/) or [minGW](https://www.mingw-w64.org/).
Some basic shell commands to familiarize yourself if you're not familiar:
* ```cd DIRECTORYNAME``` change directory
  * ```.``` the current working directory
  * ```...``` the parent directory of the current directory
* ```pwd``` path of the current working directory.
* ```ls``` list files and directory in current working directory
* ```chmod PERMS FILES``` change permissions
* ``` vi, nano, pico, code FILENAME ``` opens one of the editors and loads the specified file.

## Github
* ```git status``` shows the working branch and the status of any files.

## Useful tools
* Visual Studio Code: For writing and editing code. Download [here](https://code.visualstudio.com/download).
* Github Desktop: For helping use git on your local machine. Download [here](https://desktop.github.com/).

## Instructions 

Clone (copy) your repository to your local machine using ``git clone git@github.com:cos205/assignment-0-TEAMNAME``

Then change into the github directory by executing ``` cd assignment-0-TEAMNAME ```

Open the file ```name.txt``` using your chosen editor. For example: ```code name.txt``` will open a VSCode instance of your
file. Then edit the file by entering your name, email, and NetId.

Save your changes.

Now push your changes to github:

```git add --all```

```git commit -m "SOME TEXT DESCRIBING CHANGE"```

```git push```
