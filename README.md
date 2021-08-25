# simple shell
The shell is a program that takes commands from the keyboard via the terminal and gives them to the operating system to perform.

This project was built by Michael Davis and Emmanuel Promise
# Table of Contents
1. [Authors](#Authors)
2. [How Use](#How-Use)
3. .[explanation](#Explanation)

# Authors

 👤 **Michael Davis**

- Twitter: [@alfonsomaclean](https://twitter.com/alfonsomaclean)
- Github: [@alfonsomacleanb](https://github.com/alfonsomaclean)
- E-mail: [@alfonsomaclean](alfonsomacleandavis@gmail.com)

👤 **Emmanuel Promise**

- Github: [@Aficionado01](https://github.com/Aficionado01)
- E-mail: [@Aficionado01](emmanuelugochukwu530@gmail.com)

# How Use

## How to compile

### Requirements

- All your files will be compiled on Ubuntu 20.04.2 LTS
- Your C programs and functions will be compiled with gcc 9.3.0
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- No more than 5 functions per file

### Flags to compile

`$ gcc -Wall -Werror -Wextra -pedantic *.c`

## Explanation


## Non interactive

pass the commands in the stdin but no prints the prompt.

`$ echo "ls" | ./hsh`

## interactive

the program is execute and the prompt is print, and wait for the user.

`$ ./hsh`
`($)`