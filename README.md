# 📦File Packer Unpacker with Encryption Project (Java)

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
| File Name      | Description                  |
| -------------- | ---------------------------- |
| Packing.java   | Program used to pack files   |
| UnPacking.java | Program used to unpack files |
| README.md      | Project documentation        |


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
| Command              | Purpose                   |
| -------------------- | ------------------------- |
| javac Packing.java   | Compile packing program   |
| javac UnPacking.java | Compile unpacking program |


---

## ▶️ Run Packing Program
| Command      |
| ------------ |
| java Packing.java |


## Example Input
| Input                                   |
| --------------------------------------- |
| Enter Folder Name : DemoFolder          |
| Enter Packed File Name : PackedFile.txt |

---

## ▶️ Run UnPacking Program
| Command        |
| -------------- |
| java UnPacking |


## Example Input

| Input                                   |
| --------------------------------------- |
| Enter Packed File Name : PackedFile.txt |


---

## 🔄 Working Flow

| Step | Description                            |
| ---- | -------------------------------------- |
| 1    | User enters folder name                |
| 2    | Program scans files in folder          |
| 3    | Header created (File Name + File Size) |
| 4    | Header written to packed file          |
| 5    | File data appended                     |
| 6    | Process repeats for all files          |


Result → Single packed file created

---

## Unpacking Process

| Step | Description                  |
| ---- | ---------------------------- |
| 1    | User enters packed file name |
| 2    | Program reads header         |
| 3    | Extracts file name and size  |
| 4    | Creates new file             |
| 5    | Writes original file data    |

Result → All files restored

---

## 📊 Example
| Input Folder |
| ------------ |
| DemoFolder   |
| file1.txt    |
| file2.txt    |
| file3.txt    |



| Packed File    |
| -------------- |
| PackedFile.txt |

---

| After Unpacking |
| --------------- |
| file1.txt       |
| file2.txt       |
| file3.txt       |

---

## 👨‍💻 Author

Aditya Dipak Shejwal
<br>                                          

Java Developer                                
 Learning System Programming and File Handling 

