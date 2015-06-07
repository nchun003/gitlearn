# system call error checking

It is crucial for your `.c`/`.cpp` files to perform error checking on every system call ("syscall" for short) they employ.
Without proper error checking, when you run your program and one or more syscall returns a number that indicates an error,
say `-1`, your program would likely crash.
To do an error checking on a syscall, you would include the `stdio.h` library to utilize the `perror` function inside the conditional statement when the syscall returns an error value:
```
	if (-1==execvp(argv[0],argv)) {
		perror("execvp");
		exit(1);
	}
```
It is also good practice to pass in the name of the corresponding syscall as `perror`'s argument.
It would help you identify which syscall returned an error value.

## the `checksyscalls.sh` script
