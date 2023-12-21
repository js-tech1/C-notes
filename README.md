


### What is C?
C is a general-purpose programming language created by Dennis Ritchie at
the Bell Laboratories in 1972.
It is a very popular language, despite being old.
C is strongly associated with UNIX, as it was developed to write the UNIX
operating system.


### Why Learn C?
• It is one of the most popular programming language in the world


• If you know C, you will have no problem learning other popular
programming languages such as Java, Python, C++, C#, etc, as the
syntax is similar

• C is very fast, compared to other programming languages,
like Java and Python

• C is very versatile; it can be used in both applications and technologies

### How to create C file?
```
• In Dev c++ software File > New > Empty File.

• Save you file with ( .c ) first.c
```
Example :-
```c
#include <stdio.h>
Void main()
{
Printf(“hello world”);
}
```
```
 # include
 The line starts with #include, indicating that a header file is being included in the program.
```
```
<stdio.h> 
is the header file being included. It stands for "standard input-output header".

This header file is a standard C library that contains functions for input and output operations, such as printf and scanf.
```

## C Standard Library Functions Reference

| **Function**  | **Description**                                     |
|---------------|-----------------------------------------------------|
| `clearerr`    | Clears the end-of-file and error indicators for a stream. |
| `fclose`      | Closes the specified file stream.                  |
| `fcloseall`   | Closes all open file streams.                      |
| `fdopen`      | Associates a stream with a file descriptor.        |
| `feof`        | Checks if the end-of-file indicator is set.       |
| `ferror`      | Checks if the error indicator is set.             |
| `fflush`      | Flushes the output buffer of a stream.            |
| `fgetc`       | Reads a character from the specified stream.      |
| `fgetchar`    | Reads a character from stdin.                     |
| `fgetpos`     | Gets the current file position indicator.         |
| `fgets`       | Reads a line from the specified stream.           |
| `fileno`      | Gets the file descriptor associated with a stream.|
| `fflushall`   | Flushes all open output streams.                  |
| `fopen`       | Opens a file stream with the specified mode.     |
| `fprintf`     | Prints formatted data to a file stream.          |
| `fputc`       | Writes a character to the specified stream.       |
| `fputchar`    | Writes a character to stdout.                     |
| `fputs`       | Writes a string to the specified stream.          |
| `fread`       | Reads data from a file stream.                   |
| `freopen`     | Redirects a file stream to a new file.           |
| `fscanf`      | Reads formatted data from a file stream.         |
| `fseek`       | Sets the file position indicator.                |
| `fsetpos`     | Sets the file position indicator.                |
| `ftell`       | Gets the current file position indicator.        |
| `fwrite`      | Writes data to a file stream.                    |
| `getc`        | Reads a character from stdin.                    |
| `getchar`     | Reads a character from stdin.                    |
| `gets`        | Reads a line from stdin.                         |
| `getw`        | Reads an integer from a file stream.             |
| `perror`      | Prints a description for the last error that occurred.|
| `printf`      | Prints formatted data to stdout.                 |
| `putc`        | Writes a character to stdout.                    |
| `putchar`     | Writes a character to stdout.                    |
| `puts`        | Writes a string to stdout.                       |
| `putw`        | Writes an integer to a file stream.              |
| `remove`      | Deletes a file.                                 |
| `rename`      | Renames a file.                                 |
| `rewind`      | Sets the file position indicator to the beginning of the file.|
| `rmtmp`       | Removes temporary files created by tmpnam.      |
| `scanf`       | Reads formatted data from stdin.                 |
| `setbuf`      | Sets the buffer for a stream.                    |
| `setvbuf`     | Sets the buffer and its size for a stream.       |
| `sprintf`     | Writes formatted data to a string.               |
| `sscanf`      | Reads formatted data from a string.              |
| `strerror`    | Returns a pointer to the textual representation of the current errno value.|
| `tempnam`     | Generates a unique temporary file name.         |
| `tmpfile`     | Creates a temporary file.                        |
| `tmpnam`      | Generates a unique temporary file name.         |
| `vscanf`      | Reads formatted data from stdin using a va_list. |
| `ungetc`      | Pushes a character back onto the input stream.  |
| `vsprintf`    | Writes formatted data to a string using a va_list.|
| `unlink`      | Deletes a file.                                 |
| `vsscanf`     | Reads formatted data from a string using a va_list.|
| `vprintf`     | Prints formatted data to stdout using a va_list. |
| `vfscanf`     | Reads formatted data from a file stream using a va_list.|
| `vprintf`     | Prints formatted data to stdout using a va_list. |


• `main()` function is an entry point of the programming code to start its execution. Any code inside its curly brackets {} will be executed

• The `void` is a keyword that represents function will not return anything but a void value

• `printf()` is a function used to output/print text to the screen. In our
example it will output "Hello World"

### What Is Comment In C Language?
A comment is an explanation or description of the source code of the program.
It helps a developer explain logic of the code and improves program readability.
At run-time, a comment is ignored by the compiler

    1. Single Line Comments
    2. Multi-Line Comments

### Single line comments.
```c
#include <stdio.h>

int main() {
    //printing information
    printf("Hello world");
    return 0;
}
```
### Multi line comment.
```c
#include <stdio.h>

int main() {
    /*printing information
    Multi-Line Comment*/
    printf("Hello C");
    return 0;
}
```

### What is token in C?
    1. Keywords in C
    2. Identifiers in C ( Varible )
    3. Strings in C
    4. Operators in C
    5. Constant in C

### keyword in C
| `auto`   | `double` | `int`    | `struct` |
|----------|----------|----------|----------|
| `break`  | `else`   | `long`   | `switch` |
| `case`   | `enum`   | `register` | `typedef` |
| `char`   | `extern` | `return` | `union`  |
| `const`  | `float`  | `short`  | `unsigned` |
| `continue` | `for`  | `signed` | `void`   |
| `default` | `goto`  | `sizeof` | `volatile` |
| `do`     | `if`     | `static` | `while`  |

### Identifiers in C
Identifiers must be unique. They are created to give a unique name
to an entity to identify it during the execution of the program

## example :-
this is correct way to write

```
int a;
int jack;
int jack_joe;
int jack1;

```

don't write like this:
```
int 1a;       // Invalid: starts with a digit
int jack joe; // Invalid: contains a space
int jack-joe; // Invalid: contains a hyphen
int int;      // Invalid: uses a reserved keyword as a variable name

```
### String In C
• A String in C is nothing but a collection of characters in a linear sequence.

Example:
```c
#include<stdio.h>
int main(){
 char name[20]="hello world";
 Printf("%s",name);
 return 0;
}

```
### • Operator In C:-
    1. arethmetic :- +, -, /, *, %
    2. relastinoal :- <, >, >=, <=, ==, !=
    3. logical :- &&, ||, !
    4. bitwise :- &, |, ^, ~, <<, >>
    5. assighment :- +=, -=, *=, /=, &=, |= ...
    6. conditional :- ?
    7. increment and decrement :- a++, ++a, a--, --a
    8. sizeof

### • Constant In C:-

In C, const is a keyword used to declare constants, indicating that the associated variable's value cannot be modified after initialization. It ensures immutability, enhancing code clarity and preventing unintended changes.

#### Method 1:-
```c
#include <stdio.h>

int main() {
    // Declaring a constant variable PI with a value of 3.14
    const float PI = 3.14;

    // Printing the value of PI
    printf("The value of PI is: %f", PI);

    // Returning 0 to indicate successful program execution
    return 0;
}

```
#### Method 2:
```c
#include <stdio.h>

int main() {
    // Redefining constant 'a' from 10 to 12 using #define
    #define a 10   // Initial definition of 'a' as 10
    #undef a       // Undefining 'a' to remove previous definition
    #define a 12   // Redefining 'a' as 12
}

```

### Data Types:
| Category        | Data Type                                    | Description                                   | Example                                      |
|-----------------|----------------------------------------------|-----------------------------------------------|----------------------------------------------|
| Primitive       | `int`                                        | Integer data type for whole numbers           | `int score = 100;`                           |
|                 | `char`                                       | Character data type for single characters     | `char grade = 'A';`                         |
|                 | `float`                                      | Floating-point data type for decimal numbers | `float average = 95.5;`                     |
|                 | `double`                                     | Double precision floating-point data type    | `double pi = 3.14159;`                      |
|                 | `short`                                      | Short integer data type for smaller values    | `short distance = 500;`                     |
|                 | `long`                                       | Long integer data type for larger values      | `long population = 1000000;`                |
|                 | `_Bool`                                      | Boolean data type for true or false values    | `_Bool isTrue = 1;`                         |
| Non-Primitive   | Arrays                                       | Collection of elements of the same data type  | `int numbers[5] = {1, 2, 3, 4, 5};`         |
|                 | Structures                                   | Composite data type grouping different vars | `struct Person { char name[20]; int age; };`|
|                 | Pointers                                     | Variables storing memory addresses            | `int value = 42; int *ptr = &value;`        |
|                 | Enums                                        | Named constant values for related sets       | `enum Days { MON, TUE, WED, THU, FRI, SAT, SUN };`|
|                 | Union                                        | Special data type for storing different types| `union Data { int intValue; float floatValue; };`|


### Primitive
| Data Type | Minimum Value                           | Maximum Value                           | Size  | Format Specifier     |
|------------|-----------------------------------------|-----------------------------------------|-------|-----------------------|
| short      | -32,768                                 | 32,767                                 | 2 bytes | %d                   |
| int        | -2,147,483,648                         | 2,147,483,647                          | 4 bytes | %d                    |
| long       | -9,223,372,036,854,775,808              | 9,223,372,036,854,775,807               | 8 bytes | %ld                   |
| float      | -1.2e38                                | 1.3e38                                 | 4 bytes | %f                    |
| double     | -1.7e308                               | 1.7e308                                | 8 bytes | %.15lf                |
| char       | -128                                    | 127                                    | 1 byte | %c                    |
|      | Depends on size                        | Depends on size                        | Varies | %s                    |
