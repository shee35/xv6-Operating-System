# xv6-Operating-System
## Process Management and Scheduling in xv6

### Question 1
* It deals with creating processes in xv6 operating system such as the top and ls command in linux works.
* It has a function to get the maximum PID of the processes running currently
* It has a function that tell the number of currently running processes.

### Question 2
* Implement the system call getProcInfo(pid, processInfo). This system
call takes as arguments an integer PID and a pointer to a structure
processInfo.

### Question 3
* change the xv6 scheduler to take process
priorities into account. To that end, add new system calls to xv6 to
set/get process priorities. When a process calls setprio(n),the priority
of the process should be set to the specified value. The priority can be
any positive integer value, with higher values denoting more priority.
Also, add a system call getprio() to read back the priority set, in order
to verify that it has worked.
