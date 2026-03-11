# 📦 Packer – Unpacker Project (Java)

A Java-based File Packer and Unpacker system that combines multiple files from a folder into a single packed file and later restores the original files.

This project demonstrates Java File Handling, File Streams, and Header-based Storage Techniques.

---

## 📖 Project Overview

| Operation |	Description   |
|------------|----------------|
| Packing	 | Combines multiple files into one packed file |
| Unpacking	| Extracts original files from packed file |
| Header Creation |	Stores file name and file size |
| File Restoration	| Recreates files during unpacking |

---
## ✨ Features

| Feature	| Description |
|------------|----------------|
| 📁 Multi File Packing	 | Pack multiple files into a single file |
| 📂 File Extraction |	Restore original files |
| ⚡ Fast Processing |	Uses Java File Streams |
| 🧾 Header Based Storage |	Stores metadata before file data |

---

## 🛠 Technologies Used

| Technology |	Usage |
|----------|-----------|
| Java	| Programming Language |
| File	| Directory and File Handling |
| FileInputStream |	Reading File Data |
| FileOutputStream	| Writing File Data |
| Scanner |	Taking User Input |

---

## 📂 Project Structure
Packer-Unpacker
<br>
│
<br>
├── Packing.java
<br>
├── UnPacking.java
<br>
└── README.md

---

## ⚙️ Classes / Methods Used

| Class / Method	 | Purpose |
|------------------|---------|
| File	| Handle files and directories |
| FileInputStream	 | Read file data |
| FileOutputStream	| Write file data |
| createNewFile()	| Create packed file |
| listFiles()	| List files from directory |
| exists()	| Check file existence |
| isDirectory()	| Verify directory |
| read()	| Read bytes |
| write()	| Write bytes |

---

## ▶️ Compilation
javac Packing.java
<br>
javac UnPacking.java

---

## ▶️ Run Packing Program
java Packing.java
<br>

## Example Input.java
<br>
Enter Folder Name :
DemoFolder

<br>

Enter Packed File Name :
<br>
PackedFile.txt

---

## ▶️ Run UnPacking Program
<br>
java UnPacking.java

## Example Input

Enter Packed File Name :
<br>
PackedFile.txt

---

## 🔄 Working Flow
<br>

## Packing Process
<br>
1. User enters folder name
<br>
2. Program scans all files inside the folder
<br>
3. Header is created (File Name + File Size)
<br>
4. Header written into packed file
<br>
5. File data appended after header
<br>
6. Process repeats for all files
<br>

Result → Single packed file created

---

## Unpacking Process

1. User enters packed file name
<br>
2. Program reads header information
<br>
3. Extracts file name and size
<br>
4. Creates new file
<br>
5. Writes original data
<br>
Result → All files restored

---

## 📊 Example
## Input Folder
<br>
DemoFolder
<br>
│
<br>
├── file1.txt
<br>
├── file2.txt
<br>
└── file3.txt


## Packed File
<br>
PackedFile.txt
---

## After Unpacking
<br>
file1.txt
<br>
file2.txt
<br>
file3.txt

---

## 👨‍💻 Author

Aditya Shejwal
<br>
Java Developer
<br>
Learning System Programming and File Handling
