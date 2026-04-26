📌 Library Seat Management System
📖 Description

This is a console-based Library Seat Management System developed in C. The system allows users to view, book, and cancel library seats, while administrators can manage seat data and store it using file handling. The program uses a menu-driven interface to make navigation simple and user-friendly.

The system represents seats using a 2D array of structures, where each seat stores its booking status and the name of the user who booked it. File handling is used to save and load data so that seat information is not lost after the program ends.

🚀 Features
View all library seats in grid form
Book a seat by entering row, column, and name
Cancel an already booked seat
Prevent double booking of seats
Admin login with password protection
Save seat data to a file (library.txt)
Load previously saved seat data
Simple menu-based navigation system

🛠️ Concepts Used
Structures in C
2D Arrays
File Handling
String Handling
Menu-driven programming
Basic input validation

▶️ How to Run

Compile the program using a C compiler:

gcc main.c -o library

Run the program:

./library
Follow the menu options displayed on screen.
📂 Files
main.c → Source code of the project
library.txt → Stores saved seat data
👥 Team Members & Contributions

Member 1:

Designed the structure for seats
Implemented book() and cancel() functions

Member 2:

Designed mainMenu(), adminMenu(), and userMenu()
Handled program navigation and flow

Member 3:

Implemented saveToFile() and loadFromFile() functions
Performed testing of the complete system
🎯 Purpose

The purpose of this project is to apply basic concepts of C programming such as structures, arrays, and file handling to build a simple real-world system like a library seat reservation system.
