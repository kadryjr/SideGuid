

# Lesson 3

**Python 3 Installation on Windows**

### Step 1: Select Version of Python to Install

The installation procedure involves downloading the official Python .exe installer and running it on your system.

The version you need depends on what you want to do in Python. For example, if you are working on a project coded in Python version 2.6, you probably need that version. If you are starting a project from scratch, you have the freedom to choose.

If you are learning to code in Python, we recommend you **download both the latest version of Python 2 and 3**. Working with Python 2 enables you to work on older projects or test new projects for backward compatibility.

### Step 2: Download Python Executable Installer

1.  Open your web browser and navigate to the [Downloads for Windows section](https://www.python.org/downloads/windows/) of the [official Python website](https://www.python.org/).
2.  Search for your desired version of Python. At the time of publishing this article, the latest Python 3 release is version 3.7.3, while the latest Python 2 release is version 2.7.16.
3.  Select a link to download either the **Windows x86-64 executable installer** or **Windows** [**x86**](https://phoenixnap.com/glossary/what-is-x86) **executable installer**. The download is approximately 25MB.

### Step 3: Run Executable Installer

1. Run the **Python Installer** once downloaded. (In this example, we have downloaded Python 3.7.3.)

2. Make sure you select the **Install launcher for all users** and **Add Python 3.7 to PATH** checkboxes. The latter places the interpreter in the execution path. For older versions of Python that do not support the **Add Python to Path** checkbox, see [Step 6](https://phoenixnap.com/kb/how-to-install-python-3-windows#htoc-step-5-add-python-path-to-environment-variables-optional).

3. Select **Install Now** – the recommended installation options.

For all recent versions of Python, the recommended installation options include **Pip** and **IDLE**. Older versions might not include such additional features.

4. The next dialog will prompt you to select whether to **Disable path length limit**. Choosing this option will allow Python to bypass the 260-character MAX_PATH limit. Effectively, it will enable Python to use long path names.

### Step 4: Verify Python Was Installed On Windows

1.  Navigate to the directory in which Python was installed on the system. In our case, it is **C:\Users\_Username_\AppData\Local\Programs\Python\Python37** since we have installed the latest version.
2.  Double-click **python.exe**.
3.  The output should be similar to what you can see below:


### Step 5: Verify Pip Was Installed

If you opted to install an older version of Python, it is possible that it did not come with Pip preinstalled. Pip is a powerful package management system for Python software packages. Thus, make sure that you have it installed.

We recommend using Pip for most Python packages, especially when working in virtual environments.

To verify whether Pip was installed:

1.  Open the **Start** menu and type "**cmd.**"
2.  Select the **Command Prompt** application.
3.  Enter **pip -V** in the console. If Pip was installed successfully, you should see the following output:


