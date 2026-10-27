# Operating Systems Lab 01 — Introduction to Operating Systems

Welcome to my **Operating Systems Lab 01** repository! This lab introduces the basic concepts of operating systems and provides practical experience with Windows Command Prompt, Linux terminal commands, CPU information, process management, startup applications, system services, and graphical user interfaces as part of my **BS Software Engineering, Semester 3** at the University of Azad Jammu and Kashmir (UAJK).

## 📚 About This Lab

The purpose of this lab is to understand the role of an operating system and explore how Windows and Linux provide tools for managing and monitoring a computer system. Through practical exercises, I learned to retrieve system information, examine processor details, manage running processes, inspect startup applications and services, and compare graphical interfaces from different Windows generations.

## 🎯 Lab Objectives

- Understand the definition and role of an operating system.
- Differentiate between system software and application software.
- Practice basic Windows Command Prompt and Linux terminal commands.
- Retrieve operating system, hardware, and processor information.
- Understand CPU cores, logical processors, and clock speed.
- Explore running processes and process termination commands.
- Examine startup applications and system services.
- Explore the Windows 93 browser-based environment.
- Compare Windows 98 with modern Windows interfaces.
- Understand the difference between GUI and CLI.

## 🧠 Topics Covered

### 1. Introduction to Operating Systems

- Definition and role of an operating system.
- Management of computer hardware and software resources.
- Examples of operating systems, including Windows, Linux, macOS, and Android.
- Difference between system software and application software.
- Examples of system software and application software.

### 2. Basic Windows Command Prompt Commands

The following commands were used to retrieve basic system information:

| Command | Purpose |
|---|---|
| `date /t` | Displays the current date. |
| `time /t` | Displays the current time. |
| `hostname` | Displays the computer name. |
| `ver` | Displays the Windows version. |
| `systeminfo` | Displays detailed system information. |
| `echo %PROCESSOR_ARCHITECTURE%` | Displays the processor architecture reported by the command environment. |

### 3. Linux System Information Commands

The following Linux commands were explored for retrieving system and hardware information:

| Command | Purpose |
|---|---|
| `date` | Displays the current date and time. |
| `hostname` | Displays the computer name. |
| `uname -a` | Displays kernel and general system information. |
| `cat /etc/os-release` | Displays Linux distribution and version information. |
| `lscpu` | Displays CPU architecture, model, and processor details. |
| `free -h` | Displays memory usage in a readable format. |
| `df -h` | Displays disk space usage. |

### 4. Windows CMD vs Linux Terminal

This section compares commands used in Windows and Linux to retrieve system information, including:

- Date and time.
- Computer name.
- Operating system and kernel information.
- CPU details.
- Memory usage.
- Disk space information.

Although both command-line environments provide similar functionality, they use different commands and output formats.

### 5. CPU Cores and Processor Clock Speed

This section covers the basic concepts of CPU architecture and processor performance.

- Definition of a CPU core.
- Difference between physical cores and logical processors.
- Processor architecture: 32-bit and 64-bit.
- Identifying processor details in Windows and Linux.
- Using `lscpu`, `/proc/cpuinfo`, and `nproc`.
- Understanding CPU clock speed in GHz.
- Difference between clock speed and the number of CPU cores.

### 6. Process Management

Process management exercises focused on viewing, identifying, and terminating running processes.

#### Windows Commands

| Command | Purpose |
|---|---|
| `tasklist` | Lists currently running processes. |
| `tasklist \| findstr /i "chrome"` | Searches the process list for entries matching Chrome. |
| `tasklist /FI "PID eq 1234"` | Finds a process using its PID. |
| `taskkill /PID 1234 /F` | Forcefully terminates the process with the specified PID. |

*Note: Replace `1234` with the actual process ID. Always verify the process before terminating it.*

#### Linux Commands

| Command | Purpose |
|---|---|
| `ps aux` | Displays a detailed list of processes. |
| `top` | Monitors running processes and resource usage. |
| `pgrep -a firefox` | Searches for Firefox processes and displays matching command lines. |
| `kill 1234` | Requests termination of a process using its PID. |
| `kill -9 1234` | Forcefully terminates a process when necessary. |
| `free -h` | Displays memory usage. |

### 7. Startup Applications and System Services

This section explores how applications and services operate during system startup and normal computer use.

- Purpose of startup applications.
- How startup applications can affect boot time and resource usage.
- Using Task Manager to inspect startup applications.
- Understanding application status and startup impact.
- Exploring Windows Settings and System Configuration (`msconfig`).
- Listing running Linux services using `systemctl`.
- Checking the status of a specific service.

#### Linux Service Commands

```bash
systemctl list-units --type=service --state=running
systemctl status ssh
systemctl status sshd
```

The available service name may differ between Linux distributions.

### 8. Exploring Windows 93

The Windows 93 browser-based environment was explored to identify the main components of a desktop interface.

- Desktop.
- Desktop icons.
- Taskbar.
- Start menu, where available.
- Application windows.
- Mouse pointer.
- Menus and interactive desktop elements.

This exercise demonstrates how a desktop environment can be explored through a web browser without installing a traditional operating system.

### 9. Windows 98 vs Modern Windows

The lab compares the graphical user interface of Windows 98 with modern Windows versions.

The comparison includes:

- Desktop design and appearance.
- Start menu.
- Taskbar.
- File management.
- System settings.
- Security features.
- Hardware support.
- Internet and networking capabilities.

Windows 98 uses a classic desktop interface, while modern Windows versions provide updated visual design, improved search, and support for newer hardware and technologies.

### 10. Graphical User Interface (GUI) vs Command-Line Interface (CLI)

#### GUI — Graphical User Interface

- Uses icons, menus, buttons, and windows.
- Generally easier for beginners to learn.
- Commonly uses a mouse and keyboard.
- Example: Opening a folder through File Explorer.

#### CLI — Command-Line Interface

- Uses typed commands to interact with the computer.
- Requires knowledge of command syntax.
- Can be efficient for repetitive tasks and automation.
- Examples: Windows Command Prompt and Linux Terminal.

| Feature | GUI | CLI |
|---|---|---|
| Interaction | Clicking visual elements | Typing commands |
| Ease of use | Generally easier for beginners | Requires command knowledge |
| Speed | Convenient for visual tasks | Often efficient for repetitive tasks |
| Resource usage | May require more graphical resources | Often uses fewer graphical resources |
| Example | File Explorer | CMD or Linux Terminal |

## 🛠️ Tools and Technologies

- Windows 10
- Windows Command Prompt (CMD)
- Linux Terminal
- Ubuntu running in a virtual machine
- Windows Task Manager
- Windows Settings
- Linux `systemctl`
- Browser-based Windows 93 environment

## 📂 Lab Contents

This lab report includes practical exercises, command examples, explanations, comparison tables, and screenshots related to:

- Operating system fundamentals.
- Windows and Linux system information.
- CPU architecture and processor details.
- Process management.
- Startup applications and system services.
- Windows desktop environments.
- GUI and CLI comparison.

## 🎯 Learning Outcomes

After completing this lab, I gained practical understanding of how to:

- Explain the purpose of an operating system.
- Distinguish system software from application software.
- Retrieve system information using Windows and Linux commands.
- Identify CPU architecture and processor details.
- Understand physical cores, logical processors, and clock speed.
- View, search for, and terminate running processes.
- Inspect startup applications and system services.
- Compare desktop interfaces and command-line environments.

## 👨‍🎓 Student Information

- **Name:** Muhammad Zain Mughal
- **Roll Number:** 2025-SE-03
- **Program:** BS Software Engineering
- **Semester:** 3rd
- **University:** University of Azad Jammu and Kashmir (UAJK), Muzaffarabad
- **Course:** Operating Systems
- **Lab Number:** 01
- **Lab Title:** Introduction to Operating Systems
- **Instructor:** Engr. Seemab Khurshid

## 📌 Conclusion

This lab provided an introduction to operating systems and their practical use. By working with Windows Command Prompt and Linux terminal commands, I explored system information, processor details, process management, startup applications, and system services. I also examined desktop environments and compared graphical and command-line interfaces.

---

**Note:** This README documents Lab 01 only. The main Operating Systems repository will contain the materials and practical work for the complete course.
