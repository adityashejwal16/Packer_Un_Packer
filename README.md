##📦 Packer – Unpacker Project (Java)

A Java-based File Packer and Unpacker application that allows multiple files from a directory to be packed into a single file and later unpacked back to their original form.

This project demonstrates Java File Handling, Header Creation, Data Streams, and Basic Encryption Concepts.

---

##📑 Table of Contents
<br>
📖 Project Overview
<br>
✨ Features
<br>
🛠 Technologies Used

---

##📂 Project Structure
<br>
Packer-Unpacker
│
<br>
├── Packing.java
<br>
├── UnPacking.java
<br>
└── README.md

---
##⚙️ System Classes / Methods Used
---------------------------------
| Class / Method | 	Description |
File	Used to handle files and directories
FileInputStream	Reads data from file
FileOutputStream	Writes data into file
createNewFile()	Creates new file
listFiles()	Lists files inside directory
exists()	Checks if file exists
isDirectory()	Verifies folder
read()	Reads file data
write()	Writes file data

▶️ Compilation and Execution

🔄 Working of Project

📊 Example

👨‍💻 Author

📖 Project Overview

The Packer-Unpacker system works similar to a simple archiving tool.

Packing Process

Reads all files from a folder

Creates a header for each file

Stores file metadata and content

Combines everything into one packed file

Unpacking Process

Reads the packed file

Extracts header information

Recreates all original files

This project helps understand:

Java File Handling

Stream Processing

File Metadata Management

Data Packing Techniques

✨ Features

✅ Pack multiple files into a single file
✅ Restore files using unpacking program
✅ Header-based file storage system
✅ Efficient file reading and writing
✅ Demonstrates Java I/O Streams
✅ Simple and easy command line interface

🛠 Technologies Used
Technology	Purpose
Java	Programming Language
File	File and Directory handling
FileInputStream	Reading file data
FileOutputStream	Writing file data
Scanner	User input handling
📂 Project Structure
Packer-Unpacker
│
├── Packing.java
├── UnPacking.java
└── README.md
⚙️ System Classes / Methods Used
Class / Method	Description
File	Used to handle files and directories
FileInputStream	Reads data from file
FileOutputStream	Writes data into file
createNewFile()	Creates new file
listFiles()	Lists files inside directory
exists()	Checks if file exists
isDirectory()	Verifies folder
read()	Reads file data
write()	Writes file data
▶️ Compilation and Execution
Step 1 : Compile the Programs
javac Packing.java
javac UnPacking.java
Step 2 : Run Packing Program
java Packing

Example Input

Enter the name of folder :
DemoFolder

Enter the name of packed file :
PackedFile.txt

Example Output

Folder is present
Number of files found : 3
Packing completed successfully
Step 3 : Run UnPacking Program
java UnPacking

Example Input

Enter the name of packed file :
PackedFile.txt

Example Output

Unpacking completed successfully
Files restored in current directory
🔄 Working of Project
Packing

User enters folder name

Program scans all files inside the folder

For each file:

File name and size stored in header

Header written into packed file

File content appended after header

All files stored sequentially in single file

Result → Single Packed File

Unpacking

User enters packed file name

Program reads header information

Extracts:

File Name

File Size

Creates new file

Writes original file data

Result → All files restored

📊 Example
Input Folder
DemoFolder
│
├── File1.txt
├── File2.txt
└── File3.txt
Packed Output
PackedFile.txt
After Unpacking
File1.txt
File2.txt
File3.txt
👨‍💻 Author

Aditya Shejwal

💻 Java Developer
📚 Learning System Programming and File Handling
