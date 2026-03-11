#📦 Packer – Unpacker Project (Java)

A Java-based File Packer and Unpacker system that combines multiple files from a folder into a single packed file and later restores the original files.

This project demonstrates Java File Handling, File Streams, and Header-based Storage Techniques.

📖 Project Overview
Operation	Description
Packing	Combines multiple files into one packed file
Unpacking	Extracts original files from packed file
Header Creation	Stores file name and file size
File Restoration	Recreates files during unpacking
✨ Features
Feature	Description
📁 Multi File Packing	Pack multiple files into a single file
📂 File Extraction	Restore original files
⚡ Fast Processing	Uses Java File Streams
🧾 Header Based Storage	Stores metadata before file data
🛠 Technologies Used
Technology	Usage
Java	Programming Language
File	Directory and File Handling
FileInputStream	Reading File Data
FileOutputStream	Writing File Data
Scanner	Taking User Input
📂 Project Structure
Packer-Unpacker
│
├── Packing.java
├── UnPacking.java
└── README.md
⚙️ Classes / Methods Used
Class / Method	Purpose
File	Handle files and directories
FileInputStream	Read file data
FileOutputStream	Write file data
createNewFile()	Create packed file
listFiles()	List files from directory
exists()	Check file existence
isDirectory()	Verify directory
read()	Read bytes
write()	Write bytes
▶️ Compilation
javac Packing.java
javac UnPacking.java
▶️ Run Packing Program
java Packing

Example Input

Enter Folder Name :
DemoFolder

Enter Packed File Name :
PackedFile.txt
▶️ Run UnPacking Program
java UnPacking

Example Input

Enter Packed File Name :
PackedFile.txt
🔄 Working Flow
Packing Process

User enters folder name

Program scans all files inside the folder

Header is created (File Name + File Size)

Header written into packed file

File data appended after header

Process repeats for all files

Result → Single packed file created

Unpacking Process

User enters packed file name

Program reads header information

Extracts file name and size

Creates new file

Writes original data

Result → All files restored

📊 Example
Input Folder
DemoFolder
│
├── file1.txt
├── file2.txt
└── file3.txt
Packed File
PackedFile.txt
After Unpacking
file1.txt
file2.txt
file3.txt
👨‍💻 Author

Aditya Shejwal

Java Developer
Learning System Programming and File Handling
