# 💡 Overview of the Project
This is a simple, console-based application designed to help students manage and track their school assignments and homework. It utilizes Object-Oriented Programming (OOP) principles in Python to organize homework data (subject, assignment name, due date, and completion status) and provides a basic Command Line Interface (CLI) menu for interaction.

The project is an excellent demonstration of:

Using a class (HomeworkList) to encapsulate data and methods.

CRUD (Create, Read, Update, Delete) functionality on list items.

Basic user input handling and error management in a Python console application.

# ✨ Features
Add Assignment: Allows the user to input the subject, assignment name, and due date for a new task.

View All: Displays a formatted list of all current homework assignments, including their status (Pending or Done).

Mark Complete: Allows the user to select a task by its list number and change its status to "Done."

Delete Assignment: Allows the user to select a task by its list number and permanently remove it from the list.

User-Friendly CLI: Provides a clear, numbered menu system for easy navigation.

# 🛠️ Technologies/Tools Used
Core Language: Python 3

Programming Paradigm: Object-Oriented Programming (OOP)

Data Structures: List of Dictionaries (The self.homework list holds dictionaries, each representing an assignment).

User Interface: Standard Command Line Interface (CLI) using the built-in input() and print() functions.

# ⚙️ Steps to Install & Run the Project
Prerequisites

Ensure you have Python 3 installed on your operating system (Windows, macOS, or Linux).

Installation

Save the entire provided code block into a single text file named homework_manager.py.

Running the Application

Open your terminal or command prompt.

Navigate to the directory where you saved homework_manager.py.

Execute the script using the Python interpreter:

Bash
python homework_manager.py
The application will start and display the main menu.

# ✅ Instructions for Testing
Test the application by executing each menu option and observing the results.

Test Option 1 (Add homework):

Enter a subject, assignment, and due date.

Expected Result: A success message (✓ Added...) is printed.

Test Option 2 (View all homework):

Expected Result: A formatted table shows the assignment(s) you just added with a ⚠ PENDING status.

Test Option 3 (Mark homework as complete):

Choose option 3. The list is shown. Enter the number (e.g., 1) corresponding to the assignment you want to mark complete.

Expected Result: A success message (✓ Marked as complete...) is printed. View the list again (Option 2) to confirm the status is now ✓ DONE.

Error Test: Enter a letter (e.g., a) or an index outside the range (e.g., 5). The program should print an error message ("Please enter a valid number!" or "Invalid homework number!") and not crash.

Test Option 4 (Delete homework):

Choose option 4. The list is shown. Enter the number for the assignment you want to delete.

Expected Result: A success message (✓ Deleted...) is printed. View the list again (Option 2) to confirm the assignment is gone.

Test Option 5 (Exit):

Expected Result: The program prints a goodbye message and closes the terminal session or returns to the command prompt.
