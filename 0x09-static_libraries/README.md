main.h

This is a header file, which contains function prototypes for various string manipulation functions.

0-putchar.c

This is a C function named _putchar that is used to write a single character to the standard output. It takes a single parameter c, which is the character to be written to the standard output.
The function is defined with the int return type, which means that it returns an integer value. In this case, it returns the value returned by the write system call.

0-isupper.c

This is a C program that contains a function called _isupper which determines if a given character is an uppercase letter

0-memset.c

This is a C program that contains a function called _memset which fills a block of memory with a specific value.

0-strcat.c

This is a C program that contains a function called _strcat which concatenates two strings.

1-isdigit.c

This is a C program that contains a function called _isdigit which checks if a given integer value represents a digit.

1-memcpy.c

This is a C program that contains a function called _memcpy which is used to copy a block of memory from one location to another.

1-strncat.c

This is a C program that contains a function called _strncat which is used to concatenate two strings, taking into account a maximum number of bytes to be used from the source string.

2-strchr.c

This code defines the function _strchr which searches for the first occurrence of a character c in the string s. The function takes two parameters: a pointer to a string s and a character c to search for in the string. It returns a pointer to the first occurrence of the character c in the string s, or NULL if the character is not found.

2-strlen.c

This code defines a function named _strlen that takes a pointer to a character array (string) as its parameter and returns an integer representing the length of the string.

2-strncpy.c

This code defines a function named _strncpy that copies a given number of characters from a source string into a destination string. The function takes three parameters: a pointer to the destination string, a pointer to the source string, and an integer representing the number of characters to copy.

3-islower.c

This code defines a function named _islower that checks if a given character is lowercase or not. The function takes a single parameter, an integer representing the ASCII value of the character to check.

3-puts.c

This code defines a function named _puts that prints a given string to the standard output, followed by a newline character. The function takes a single parameter, a pointer to the string to print.

3-strcmp.c

This code defines a function named _strcmp that compares the values of two strings and returns the difference between the first two differing characters as an integer. The function takes two parameters, both pointers to the strings to compare.

3-strspn.c

This code defines a function named _strspn that calculates the length of the initial segment of a string that consists entirely of characters from a second string. The function takes two parameters, both pointers to the strings to analyze.

4-isalpha.c

This code defines a function named _isalpha that takes a single integer argument c. The function returns an integer value of 1 if the character c is an alphabet letter, and 0 otherwise.
Let's go through the code line by line:

4-strpbrk.c

This code defines a function named _strpbrk that takes two string pointers as arguments - s and accept. The function returns a pointer to the first occurrence of any character in accept in the string s.

5-strstr.c

This code defines a function named _strstr that takes two string pointers as arguments - haystack and needle. The function searches for the first occurrence of the needle string in the haystack string and returns a pointer to the first character of the match. If the needle string is not found, the function returns a null pointer.

6-abs.c

This code defines a function named _abs that takes an integer n as input and computes its absolute value. The function returns the absolute value of the input integer.

9-strcpy.c

This code defines a function named _strcpy that copies a string from a source to a destination. The function takes two parameters, a dest pointer that points to the destination string, and a src pointer that points to the source string. The function returns the destination string after copying the source string into it.

100-atoi.c

This code defines a function named _atoi that takes a pointer to a character string as input and returns an integer.

create_static_lib.sh

This is a shell script named create_static_lib.sh that is used to create a static library from a collection of C source files in the current directory.

