# Bakery-Algorithm-Implementation
A C++ implemetation of bakery algorithm. The project was implemented in a linux enviroment.
Each thread, represents an actor trying to access shared memory, and the bakery algorithm is used to synchronize
the threads.

There is no use of atomic variables whatsoever.

The program runs for a predifined amount of time (5 secs). This time can be changed by changing the very last sleep() function parameter in main().
