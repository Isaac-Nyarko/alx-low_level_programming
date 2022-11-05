argc and argv
So far, all the programs we have written can be run with a single command. For example, if we compile an executable called myprog, we can run it from within the same directory with the following command at the GNU/Linux command line:

./myprog
However, what if you want to pass information from the command line to the program you are running? Consider a more complex program like GCC. To compile the hypothetical myprog executable, we type something like the following at the command line:

gcc -o myprog myprog.c
The character strings -o, myprog, and myprog.c are all arguments to the gcc command. (Technically gcc is an argument as well, as we shall see.)

Command-line arguments are very useful. After all, C functions wouldn't be very useful if you couldn't ever pass arguments to them -- adding the ability to pass arguments to programs makes them that much more useful. In fact, all the arguments you pass on the command line end up as arguments to the main function in your program.
