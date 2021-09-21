The pthread libraries are standard based thread API for coding languages like C/C++. It allows the formation of a new simultaneous process flow. It works well on multi core systems. It gives access to the program to control different works that got overlapped in time.  Each work is known as thread.A thread is a semi process that have its own stack.

Thread Basics:-
This process includes some steps:-
Thread Creation
Termination
Synchronization
Scheduling
Data Management 
Process Interaction

Each thread has a different:-
Thread Id
Set of registers, stack pointers
Stack for local variables, return addresses
Signal mask
Priority
Return value: errno

If OK then the pthread function returns 0.
For using the pThread interface we should use the header named pthread.h at the starting of the CPP script.

Difference between process and thread 
A process is. a program that is under execution.
A thread is a floaty process that is managed on one’s own by a synchronizer.
Process needs more time for context timing while threads need less time.
Process are independent while threads does not.
Communication requires more time between process while threads needs less time.
If a process is blocked then also execution is done while in threads if blocked then everything gets stopped.
Process needs more time for creation while threads require less time.
Threads are a popular way to improve application through parallelism. For example, in a browser, multiple tabs can be different threads.

Thread operate faster than process because of the reasons mentioned below:
1) Thread creation is much faster.
2) Context switching between threads is much faster.
3) Threads can be terminated easily
4) Communication between threads is faster.
The thread library supports 3 Synchronization methods:-
Mutexes - Block access to variables by other threads
Joins - Make a thread wait until others are terminated.
Condition Variables - data type pthread_cond_t
 
Applications of Pthreads
The major benefit of multithreaded programs over non threaded ones is in their ability to concurrently execute tasks. However, in providing concurrency, multithreaded programs introduce a certain amount of overhead. If you introduce threads in an application that can’t use concurrency, you’ll add overhead without any performance benefit.
 



