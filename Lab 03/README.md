# Operating Systems Lab — Lab Task 03: DOS Commands

Welcome to my **Operating Systems Lab Task 03** repository. This lab focuses on learning and practicing basic DOS/Windows Command Prompt (CMD) commands for system interaction, directory management, and file handling.

## 📚 Lab Information

- **University:** The University of Azad Jammu and Kashmir, Muzaffarabad
- **Department:** Software Engineering
- **Student Name:** Muhamad Zain Mughal
- **Roll Number:** 2025-SE-03
- **Program:** BS Software Engineering
- **Semester:** 3rd
- **Session:** 2025–29
- **Course:** Operating Systems
- **Course Code:** CSC-533
- **Instructor:** Engr. Seemab Khurshid
- **Lab Number:** 03
- **Lab Title:** DOS/Windows CMD Commands
- **Lab Assigned Date:** 20 October 2026

## 🎯 Objectives

The objectives of this lab are to:

- Understand basic Windows Command Prompt commands.
- Check file-extension associations.
- Navigate between directories.
- Identify the currently signed-in user.
- Clear the Command Prompt screen.
- Display help for available commands.
- View and manage files and directories.
- Create directories and empty text files.
- Verify the results of commands using CMD.

## 🛠️ Commands Practiced

| Command | Purpose | Example |
|---|---|---|
| `assoc` | Displays or changes file-extension associations. | `assoc .txt` |
| `cd` | Displays or changes the current directory. | `cd C:\Users` |
| `whoami` | Displays the currently signed-in user. | `whoami` |
| `cls` | Clears the CMD screen. | `cls` |
| `del` | Deletes one or more files. | `del test.txt` |
| `help` | Displays help for CMD commands. | `help` |
| `date /t` | Displays the current system date. | `date /t` |
| `echo` | Displays a message in CMD. | `echo Hello from CMD` |
| `exit` | Closes the current CMD session. | `exit` |
| `dir` | Lists files and subdirectories. | `dir` |
| `mkdir` | Creates a directory. | `mkdir Lab` |
| `type nul` | Creates an empty file when redirected to a filename. | `type nul > file1.txt` |

## 💻 Practical Task: Create and Verify Files

In this practical task, I created a directory named `LabFiles` on the C drive and created three empty text files inside it.

### Step 1: Open Command Prompt

I press `Windows + R`, type `cmd`, and press Enter to open Command Prompt.

### Step 2: Create the Directory

I type the following command and press Enter to create the `LabFiles` directory.

```cmd
mkdir C:\LabFiles
```

### Step 3: Navigate to the Directory

I type the following command to change the current directory to `C:\LabFiles`.

```cmd
cd /d C:\LabFiles
```

### Step 4: Create the First File

I type the following command to create an empty file named `file1.txt`.

```cmd
type nul > file1.txt
```

### Step 5: Create the Second File

I type the following command to create an empty file named `file2.txt`.

```cmd
type nul > file2.txt
```

### Step 6: Create the Third File

I type the following command to create an empty file named `file3.txt`.

```cmd
type nul > file3.txt
```

### Step 7: Verify the Files

I type the `dir` command to display the contents of the directory and verify that all three files have been created.

```cmd
dir
```

### Expected Output

The directory listing should include:

```text
file1.txt
file2.txt
file3.txt
```

## 📸 Screenshots and Evidence

The lab report contains screenshots demonstrating:

- File-extension association using `assoc .txt`.
- Directory navigation using `cd`.
- User identification using `whoami`.
- Clearing the CMD screen using `cls`.
- File deletion using `del`.
- Command help using `help`.
- Displaying the date using `date /t`.
- Printing a message using `echo`.
- Closing CMD using `exit`.
- Listing directory contents using `dir`.
- Creating directories using `mkdir`.
- Creating and verifying empty text files.

## ⚠️ Precautions

- I check the current directory before running file-management commands.
- I use `del` carefully because deleted files may not go to the Recycle Bin.
- I avoid deleting important files during practical work.
- I save my work before using `exit` to close CMD.
- I verify the output after executing each command.

## ✅ Result

I successfully practiced basic Windows Command Prompt commands and created the `LabFiles` directory containing three empty text files: `file1.txt`, `file2.txt`, and `file3.txt`. I verified the files using the `dir` command.

## 📝 Conclusion

This lab helped me understand how to use Windows CMD for basic system interaction and file and directory management. I learned how to check file associations, navigate directories, identify the current user, display command help, create directories and files, and verify command results.

---

**Course:** Operating Systems  
**Lab:** Task 03 — DOS/Windows CMD Commands  
**Program:** BS Software Engineering, Semester 3
