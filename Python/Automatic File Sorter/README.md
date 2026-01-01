# Automatic File Sorter (Python)

## Project Overview
This project uses Python to organize files within a directory by sorting them into folders based on file type. The script demonstrates basic file system operations, directory handling, and conditional logic.

---

## Objective
- Practice working with file system operations in Python  
- Organize files based on file extensions  
- Apply conditional logic to manage file movement safely  

---

## Tools & Libraries
- Python  
- os  
- shutil  

---

## How the Script Works
The script performs the following steps:

- Scans a specified directory for files  
- Creates destination folders if they do not already exist  
- Moves files into categorized folders based on file extensions  
- Prevents overwriting files that already exist in the destination folders  

---

## File Types Handled
- CSV files  
- Image files (`.png`)  
- Text files (`.txt`)  

---

## Usage
1. Update the directory path variable in the script to point to the target folder  
2. Run the script  
3. Files are sorted into their corresponding folders based on file type  

---

## Notes
The script can be extended to support additional file types by adding new file extensions and destination folders.
