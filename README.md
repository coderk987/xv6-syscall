## Adding Syscalls to xv6

The Project has the following new commands that initiate new syscalls
1. listfd => calls the lsfd() syscall => prints info about all the file descriptors of a process
2. listp => calls the lsproc() syscall => prints info about all actvie processes in the OS
3. pikachu => calls the pokeball syscall ---> experiment syscall and command

How to Run?
Use the command "make qemu-nox" on a Linux based system

## Adding MLFQ Scheduling

In proc.c a queue implementation has been added to simulate process queues
All process's start with the highest priority and demote and promote based on the ticks they use
q3 => 8 ticks, q2 => 16 ticks, q1 => 32 ticks, q0 => 64 ticks
