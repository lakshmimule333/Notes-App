Notes App

NAME : MULE LAKSHMI NARAYANAMMA

Objective: The goal of this task is to create a command-line Notes Manager in Java that allows users to:

Write notes to a file.

View all saved notes from the file.

Exit the program safely.

This project demonstrates how to persist user input in text files, which is one of the most essential skills in backend and system-level Java development.

Tools and Technologies:

Programming Language: Java (JDK 8 or above)

Editor/IDE: VS Code, IntelliJ IDEA, Eclipse, or any Java editor

Runtime: Terminal or Command Prompt

Concepts Covered:

File Handling in Java

Writing data to a file using FileWriter

Reading data from a file using FileReader and BufferedReader

Understanding append (true) vs overwrite (false) modes in FileWriter

Exception Handling

Handling IOException and FileNotFoundException

Using try-with-resources for automatic resource management

Differentiating between checked and unchecked exceptions

User Input and Loops

Using Scanner for reading console input

Implementing a menu-driven program with loops and switch-case

Code Structure and Modularity

Separating functionality into methods such as writeNote and readNotes

Maintaining clean, reusable, and readable code

Features of the Notes App:

Write Notes: Users can enter any text, which is saved into a file (notes.txt)

Read Notes: Displays all previously saved notes line by line

Persistent Storage: Notes remain saved even after the program ends

Error Handling: Gracefully handles missing files, read/write errors, and invalid user input

Menu-Driven Interface: Easy to navigate using numbers (1, 2, 3)

Workflow of the Program:

Start the program.

Show the main menu with options to write a note, view notes, or exit.

User chooses an option.

If option 1, the program asks for a note and saves it in notes.txt.

If option 2, the program reads and displays notes.

If option 3, the program exits safely.

The menu repeats until the user selects Exit.

Key Java Classes Used:

FileWriter: Writes text data into a file

FileReader: Reads characters from a file

BufferedReader: Reads text efficiently line by line

Scanner: Reads user input from console

Best Practices Learned:

Always close file streams or use try-with-resources

Use BufferedReader instead of plain FileReader for efficiency

Validate user input before processing

Handle exceptions to prevent program crashes

How to Run:

Clone this repository git clone https://github.com/lakshmimule333/NotesApp.git

cd NotesApp

Compile the Java program javac NotesApp.java

Run the program java NotesApp

Deliverables:

A working NotesApp.java file

A GitHub repository containing:

NotesApp.java (source code)

README.md (documentation of the project)

notes.txt (optional: sample output file with notes)

Learning Outcome: By completing this task, you will:

Gain hands-on experience with Java File I/O APIs

Understand exception handling and resource management

Learn how to design a menu-driven console application

Build confidence in writing real-world Java programs that persist data

OUTPUT : 
<img width="1919" height="995" alt="Image" src="https://github.com/user-attachments/assets/860777a4-3a1a-42b4-8cdf-8002ddac06bf" />
