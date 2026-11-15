# Operating Systems Lab 04 — fork() Process Demo

In this lab, I implemented a C++ program using the `fork()` system call to create a child process.

I used `getpid()` to display the process ID of the parent and child processes. I used `getppid()` to display the parent process ID of the child process.

I also used `waitpid()` to make the parent process wait until the child process completed its execution. Finally, I used `WIFEXITED()` and `WEXITSTATUS()` to check the child's termination status and display its exit code.

Through this practical, I learned how process creation and synchronization work in an operating system using C++ and POSIX system calls.
