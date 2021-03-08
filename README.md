# Operating-system
Operating system code

An opertaing system written with assembly and c, currently consists of a bootsector code, kernel code, drivers (currently for the keyboard and screen), code to interact and handle the cpu, and code to handle with memory and strings.
next i intend to add user mode, i also have already written a more advanced code for the shell that adds more commands and a text editor, but in order to use it i first need to add file management.
i also intend to add networking in the future.

the priority right now is to deal and upgrade the memory management and add a file management system (which will make the kernel bigger), and deal with more hardware interrupts.
I will add an implementation of memory allocation in c which will be the sketch to the idea of memory allocation (It's just the main idea and will of course be implemented differently to be adapted to the os and deal better with allocating the memory).
