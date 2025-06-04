# GitHub-User-Interface
final project 
# Calculator
This Python code provides a basic command-line calculator. It allows users to perform four fundamental arithmetic operations: addition, subtraction, multiplication, and division. The program presents a simple menu, prompts the user to select an operation, and then asks for two numbers. It includes basic error handling to catch non-numeric input and prevents division by zero. The result of the chosen operation is then displayed to the user.

## Requirements
Python Interpreter: The most crucial requirement is having Python installed on your system. The calculator code is written in standard Python, so any recent version (Python 3.6 or newer is generally recommended) will work perfectly.

## Installation
Here are the step-by-step instructions to install Python and then run the calculator code.

Installation Steps
Step 1: Install Python
First, you need to install the Python interpreter on your computer.

Download Python:

Go to the official Python website: python.org/downloads
The website should automatically detect your operating system (Windows, macOS, Linux) and recommend the latest stable version of Python 3. Download the appropriate installer.
Run the Installer:

For Windows:
Double-click the downloaded .exe file.
CRITICAL: On the first screen of the installer, make sure to check the box that says "Add python.exe to PATH" (or similar wording). This step is very important as it allows you to run Python from your command prompt easily.
Click "Install Now" and follow the prompts.
For macOS:
Double-click the downloaded .pkg file.
Follow the on-screen instructions to complete the installation.
For Linux:
Python is often pre-installed on many Linux distributions. You can check by opening your terminal and typing python3 --version.
If it's not installed or you need a newer version, use your distribution's package manager (e.g., sudo apt-get install python3 for Debian/Ubuntu, or sudo dnf install python3 for Fedora).
Step 2: Verify Python Installation
After installation, it's a good idea to confirm that Python was installed correctly and is accessible from your command line.

Open your Command Prompt/Terminal:
Windows: Search for "CMD" or "Command Prompt" in the Start menu.
macOS: Search for "Terminal" in Spotlight (Cmd + Space) or find it in Applications > Utilities.
Linux: Open your preferred terminal application.
Type the command:
```Bash
python --version
```
or, for some systems:
```Bash
python3 --version
```
You should see output similar to Python 3.x.x (e.g., Python 3.10.12), confirming that Python is installed.
Step 3: Run the Calculator Code
Once Python is set up, running the calculator code is straightforward.

Save the Code:

Copy the Python calculator code (provided in previous responses).
Paste it into a plain text editor (like Notepad on Windows, TextEdit on macOS, or VS Code/Sublime Text/Atom).
Save the file with a .py extension (e.g., calculator.py). Remember where you save this file!
Navigate to the File's Directory:

Open your Command Prompt/Terminal again.
Use the cd command to navigate to the directory where you saved your calculator.py file.
Example: If you saved it in a folder called PythonProjects on your Desktop, you might type:
cd Desktop\PythonProjects (Windows)
cd Desktop/PythonProjects (macOS/Linux)
Run the Script:

Once you're in the correct directory, type the following command and press Enter:
```Bash
python calculator.py
```
or:

```Bash
python3 calculator.py
```
The calculator program will start running in your terminal, and you'll see the "Select operation:" menu.

## Use
Run the Calculator: Open your command prompt or terminal, navigate to the folder where you saved your calculator.py file, and run it using the command:

```bash
python calculator.py
```
(or python3 calculator.py if needed).

Select Operation: The calculator will display a menu:

Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice(1/2/3/4):
Enter the number corresponding to the operation you want to perform (1 for addition, 2 for subtraction, etc.) and press Enter.

Enter Numbers: Next, the calculator will ask for the two numbers for your operation:

Enter first number:
Type the first number and press Enter. Then it will ask for the second number:

Enter second number:
Type the second number and press Enter.

View the Result: The calculator will display the result of the operation. If you entered something that wasn't a number or tried to divide by zero, it will show an error message.


