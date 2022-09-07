# Unix Memory Profiler

This is a Heap Memory Manager built in C for Unix-based Operating Systems. 

This library enables you to allocate and free memory, catch memory leaks,remove internal/external fragmentation problems, and show memory statistics currently in use.

## How To Run This Program

`1. Clone Repository to your local machine.`

`2. Open Clone in IDE or terminal of your choice.`

`3. Run the following command to compile: gcc -g -c testapp.c -o testapp.o gcc -g -c mm.c -o mm.o gcc -g -c gluethread/glthread.c -o gluethread/glthread.o gcc -g testapp.o mm.o gluethread/glthread.o -o exe`

<img src="Screenshot from 2021-06-01 17-01-01.png"/>
<img src="Screenshot from 2021-06-01 17-01-14.png"/>
<img src="Screenshot from 2021-06-01 17-01-50.png"/>
