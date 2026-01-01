# Automatic File Sorter in File Exploration (Python)

This project is a Python automation script that organizes files in a directory by moving them into folders based on file type.

## Objective
To demonstrate Python automation, file handling, and directory management using real-world file system operations.

## How It Works
- Scans a target directory for files
- Creates destination folders if they do not already exist
- Moves files into categorized folders based on file extensions
- Prevents overwriting existing files

## File Types Handled
- CSV files 
- Image files (.png)
- Text files (.txt) 

## Tools & Libraries
- Python
- os
- shutil

## Usage
1. Update the `path` variable to point to the directory you want to organize.
2. Run the script.
3. Files will automatically be sorted into their respective folders.

## Example Use Case
This script can be used to organize folders such as Downloads or Desktop, reducing manual file management and improving productivity.

## Notes
The script can be easily extended to support additional file types by adding new extensions and folders.

