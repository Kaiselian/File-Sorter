# File Sorter

## Overview
The File Sorter is a simple Python script that organizes files in a specified directory by grouping them into folders based on their file extensions. It helps to keep your directories clean and well-organized by automatically moving files into appropriate subfolders.

## Features
- Automatically identifies and sorts files by their extensions.
- Creates new folders for file extensions if they do not already exist.
- Moves files into the corresponding folders.

## Requirements
- Python 3.x
- `os` module (comes with Python standard library)
- `shutil` module (comes with Python standard library)

## Installation
1. Make sure you have Python 3 installed on your system. You can download it from [python.org](https://www.python.org/).

2. Clone the repository or download the `File-Sorter.py` script.

    ```bash
    git clone https://github.com/Kaiselian/File-Sorter.git

## Usage
1. Open a terminal or command prompt.
2. Navigate to the directory where File-Sorter.py is located.
3. Run the script by typing:

    ```bash
    python File-Sorter.py

4. When prompted, enter the path to the directory you want to organize.

    ```bash
    Enter Path: /path/to/your/directory

## Example
Suppose you have a directory with the following files:
    
    ```bash
    /example_directory
        - document.pdf
        - photo.jpg
        - script.py
        - archive.zip

After running the script and entering the path to /example_directory, the directory will be organized as follows:

    ```bash
    /example_directory
    /pdf
        - document.pdf
    /jpg
        - photo.jpg
    /py
        - script.py
    /zip
        - archive.zip

## Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

