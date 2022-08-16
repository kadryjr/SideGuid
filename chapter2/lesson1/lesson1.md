



# Lesson 1

The Command Line

The **command line** is a more intimate way of interacting with your computer (than say, Finder on Mac or Explorer on Windows). We’ve already used it to install Python3, pip3, virtualenv and virtualenvwrapper during orientation. You might also hear folks referring to the command line as the **shell**, **Terminal** (on Mac) or **Babun** (on Windows).

Soma has compiled a ton  of common shell commands! I won’t repeat them all here now, but remember pwd, ls, cd [foldername], cd .. are really helpful when you are moving around your computer using the command line. A few other things to keep in mind:

-   rm -rf: this deletes everything on your computer! So don’t use this. WHY AM I EVEN REPEATING IT HERE?
-   You can add **flags** to commands to instruct shell to do specific things or structure its output in a specific way. A few helpful flags to add to the ls command:

-   -l: displays more information about your files and folders (you’d enter it as ls -l in your shell)
-   -h: makes the displayed filesize numbers human readable!
-   -a: all, shows you hidden files, usually important stuff your computer doesn’t want you to deal with.
-   You can use a bunch of flags together ls -lh or ls -lha

-   **A few helpful** **cd** **commands:**

-   cd .. moves you “up” one directory
-   When you see _~_ in terminal, it means you’re in your home directory.
-   cd ~: takes you directly to your home directory
-   cd ~/Downloads: takes you directly to your Downloads folder
-   cd [drag the folder from Finder into Terminal]: it’ll autocomplete the path to that folder! This only works on Macs.

-   If your command line is running something it shouldn’t be, use Ctrl+C to escape/exit.
-   clear will do exactly as it sounds; your Terminal/Babun shell will be cleared of all commands and output.
-   File and folder names have to be typed exactly as is! cd desktop and cd Desktop are different (you probably want to use the latter).
