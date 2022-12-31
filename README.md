# operating-system
```
test.c -> compile -> test.o -> test.exe

.exe file is store in binary in hard disk memory cells. when the executable file is run, 
the binary lines are loaded in ram's empty cell line by line

Processor has two parts, processing part and register part
Processing part is reponsible to run the commands

Register part has a register called pointing register. pointing register points to a command and processing part executes it

The file which is loaded in the ram and the processing part starts running it then the whole thing is called a process
Process is a virtual computer

what is the need of process?
To run multiple files at a time. Process gives the exe file a feel that it's a computer on it's own

Context switching
pointing register switches between different processes to run them simultaneously. This is called context switching

Process Control Block (PCB)
Pointing register saves at which point it left the process to context switch another. where it saves is called PCB

Concurrency
If one processor runs and does context switching to run several files, is called concurrency

core i3 has 3 cores and one core has two threads. it has 6 threads (as per intel). these threads are virtual cpu. so it has 6 virtual cpu / logical cpu
Parallel programming is when at a time 6 processor is running 6 process at a time

Now comes real thread.
Process has threads. thread is a virtual process.
One process has one thread by default

Javascript is a single threaded language. Because javascript has only one thread and it runs the code component one at a time. that's why its a single threaded language


