

# Lesson 2

**Installing and Updating Python on Mac**

I have two pieces of news for you; one is good, the other bad. The good news is that for the sake of compatibility with legacy systems, Python 2.7 is pre-installed on your Mac, but the bad news is that Python 2.7 has been retired. Therefore, it isn’t recommended for new developments. So, if you want to take advantage of the new Python version with its many features and improvements, you need to install the latest Python alongside the version that comes pre-installed on macOS. Before we start installing the latest version of Python, let’s see why there are different versions of the same programming language. All programming languages evolve by adding new features over time. The programming language developers announce these changes and improvements by increasing the version number.

**Install Python 3 as a part of the Command Line Developer Tools**

To check the current version of Python that is already installed, open the Terminal application by typing command + space and then spelling out terminal and hitting return. Now, type the following command, and then hit return to see that you have Python 2.7 pre-installed on your Mac:

% python --version  
Python 2.7.18

Now, try the following command to check whether or not Python 3 is installed on your Mac:

~ % python3 --version

The following message will probably appear on the Terminal window,

xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.

And alongside the Terminal window, a dialog box will automatically appear that says this command requires the command line developer tools. First, let’s identify the command-line developer tools. To put it briefly, the command line developer tools package is a set of tools mostly used in the development process. They help run specific commands, such as make, git, python3, etc. So, although there are other ways to install Python 3.x on Mac without installing the command line developer tools, I recommend you install it because it provides a string of tools for development on Mac. To install the package, click on the Install button, and follow the steps to complete the installation process. Once the installation process is complete, rerun the previous command. Yes, Python 3.x is installed on your Mac.

~ % python3 --version  
Python 3.8.9

**Install Python 3 with the Official Installer**

Downloading the latest Python version from the official Python website (python.org) is the most common (and recommended) method for installing Python on a Mac. Let’s try it out.

1. First, download an installer package from the Python website. To do that, visit [https://www.python.org/downloads/](https://www.python.org/downloads/) on your Mac; it detects your operating system automatically and shows a big button for downloading the latest version of Python installer on your Mac. If it doesn’t, click the macOS link and choose the latest Python release.
![Image 1](https://drive.google.com/file/d/12ZIObIYzU5eHYxyRpTkfH8JQXZqNFGkJ/view?usp=sharing)
2. Once the download is complete, double-click the package to start installing Python. The installer will walk you through a wizard to complete the installation, and in most cases, the default settings work well, so install it like the other applications on macOS. You may also have to enter your Mac password to let it know that you agree with installing Python.
![Image 2](https://drive.google.com/file/d/10dpA0VZiijTpC520ET2w-XgNbsjB42Md/view?usp=sharing)


3. When the installation completes, it will open up the Python folder.
![Image 3](https://drive.google.com/file/d/1PJeX92X6gzX6ZeYbQZFar_PO6gxIt2rL/view?usp=sharing)


4. Let’s verify that the latest version of Python and IDLE installed correctly. To do that, double-click IDLE, which is the integrated development environment shipped with Python. If everything works correctly, IDLE shows the Python shell as follows:

![Image 4](https://drive.google.com/file/d/1nwPd57lESWapLYN5DF6GFqhPutuR3ki7/view?usp=sharing)

5. Let’s write a simple Python code and run it in IDLE. Type the following statement, and hit the return key.
```
print(“Hello, World!”)
```

![Image 5](https://drive.google.com/file/d/1r3rCwcI_C054IlHTsSfLQ8pRnONI5ttZ/view?usp=sharing)
