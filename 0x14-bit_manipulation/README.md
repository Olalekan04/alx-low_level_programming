0x14. C - Bit manipulation
Requirements
General
    • Allowed editors: vi, vim, emacs
    • All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
    • All your files should end with a new line
    • A README.md file, at the root of the folder of the project is mandatory
    • Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
    • You are not allowed to use global variables
    • No more than 5 functions per file
    • The only C standard library functions allowed are malloc, free and exit. Any use of functions like printf, puts, calloc, realloc etc… is forbidden
    • You are allowed to use _putchar
    • You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
    • In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
    • The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called main.h
    • Don’t forget to push your header file
    • All your header files should be include guarded

Tasks
    • 0. 0
        ◦ 0-binary_to_uint.c: C function that converts a binary number to an unsigned int.
        ◦ The parameter b is a pointer to a string of 0 and 1 characters.
        ◦ If b is NULL or there are one or more characters in b that are not 0 or 1 - returns 0.
        ◦ Otherwise - returns the converted number.
    • 1. 1
        ◦ 1-print_binary.c: C function that prints the binary representation of a number.
    • 2. 10
        ◦ 2-get_bit.c: C function that returns the value of a bit at a given index.
        ◦ Indices start at 0.
        ◦ If an error occurs - returns -1.
        ◦ Otherwise - returns the value of the bit at the given index.
    • 3. 11
        ◦ 3-set_bit.c: C function that sets the value of a bit at a given index to 1.
        ◦ If an error occurs - returns -1.
        ◦ Otherwise - returns 1.
    • 4. 100
        ◦ 4-clear_bit.c: C function that sets the value of a bit at a given index to 0.
        ◦ If an error occurs - returns -1.
        ◦ Otherwise - returns 1.
    • 5. 101
        ◦ 5-flip_bits.c: C function that returns the number of bits needed to be flipped to get from one number to another.
    • 6. Endianness
        ◦ 100-get_endianness.c: C function that checks the endianness.
        ◦ If big-endian - returns 0.
        ◦ If little-endian - returns 1.
    • 7. Crackme3
        ◦ 101-password: File containing the password for the crackme3 executable.

