# Adding Syscalls to xv6

The Project has the following new commands that initiate new syscalls
1. listfd => calls the lsfd() syscall => prints info about all the file descriptors of a process
2. listp => calls the lsproc() syscall => prints info about all actvie processes in the OS
3. pikachu => calls the pokeball syscall ---> experiment syscall and command

How to Run?
Use the command "make qemu-nox" on a Linux based system