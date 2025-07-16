# FreeWindowsOS
## What is it about ?
Since windows is the most popular choice of operating system, most applications are specificaly designed to run on it.

Why recreating another operating system instead of creating a compatibility layer for every Linux based distros just like Wine ?

> Conflicts.

Windows has its own architecture, I.E. :  Paths (C:\ ; usage of "\\" instead of "/") , APIs (Win32API) , Registry System , Drivers....

That said, when you try to integrate a windows-based application, many conflicts appear and it becomes more and more difficult to keep track of every interactions between the compatibility layer and the host system.

## Why not recreating a whole Operating System from scratch ?
I don't have the skills to do such task, and such work requires an amazing amount of time and patience (which i barely have ngl).
Just think about reprogramming a whole process scheduler for the processor, reprogramming a memory manager, drivers, and network protocols, AND many other critical stuff...

Checkout reactos which does the job very well (while still beeing in Alpha phase, you are already able to build an ISO and try the system and install some softwares !)
https://github.com/reactos/reactos


## Basic concepts.
I will detail how this new OS should be designed, this is still a vague idea though.
