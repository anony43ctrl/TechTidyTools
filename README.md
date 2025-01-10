# File Deleter Utility
Efficiently delete files based on their last modified date. 🧹

This branch contains a utility program to help you delete files in a specified directory based on their last modified date.
Whether you want to clean up old logs, expired backups, or outdated files, this tool makes it quick and easy to automate the process.

**Features**
📅 Date-Range Filtering: Target files based on a specific date range.
📂 Directory Selection: Specify the folder to clean up.
🚀 Fast and Lightweight: Efficiently processes and deletes files without bloating your system.
🔧 Customizable: Easily edit the source code to adjust settings for your needs.


## How to Use

### Step 1: Clone the Repository
Clone the repository and switch to the `File-Deleter-Utility` branch:

```bash
git clone https://github.com/anony43ctrl/TechTidyTools.git
cd TechTidyTools
git checkout File-Deleter-Utility
```
### Step 2: Compile and run the Program
Use a C++ compiler (e.g., Microsoft Visual Studio or Command Prompt) to compile the code.
Run the following command:
```bash 
cl /EHsc File_Deleter.cpp
File_Deleter.exe

```

### Step 3: 

Specify the Folder:
When the program runs, you will be asked to enter the path to the directory you want to clean up. Make sure the folder exists and the path is valid.

Enter the directory path: C:\directory\

Set the Date Range:
The program will prompt you for the start and end dates for the files to be deleted. For example, if you want to delete files modified in 2023, you will need to enter: 

Start Date:
Year: 2023
Month: 1
Day: 1

End Date:
Year: 2023
Month: 12
Day: 31

The program will delete files that were modified between these dates.
