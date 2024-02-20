
# Simple shell

![hsh logo](https://whoinventedme.files.wordpress.com/2016/06/image-1047.jpg?w=816)

This project is about writing a simple UNIX command interpreter (shell) in C. A shell is a program that takes commands from the user and executes them by invoking other programs. A shell can also have built-in functions that perform various tasks without calling external programs. The name of our shell is hsh, and it has some basic features and limitations.


## Badges

![Status: Active](https://img.shields.io/badge/Status-Active-green.svg)

![Version: 1.0](https://img.shields.io/badge/Version-1.0-orange.svg)

![Language: C](https://img.shields.io/badge/Language-C-purple.svg)
## Features

- Our shell can read and execute commands and arguments from the standard input or from a file.
- Our shell can handle the PATH variable, which contains the directories where the executable programs are located.
- Our shell can handle the following built-in commands: exit, env, and setenv.
- Our shell can handle errors and display appropriate messages to the standard error.
- Our shell can handle the end-of-file (EOF) condition.

## Authors

- [@Mostafa-Naguib](https://www.github.com/Mostafa-Naguib)


## Installation

To install and run our shell, follow these steps:

```
  - Clone this repository: git clone [6](https://github.com/underscoDe/simple_shell)
  - Navigate to the directory: cd simple_shell
  - Compile the code: gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
  - Run the shell: ./hsh
  - Enter commands and arguments as you wish.
```
    
## Usage/Examples

```
$ ls -l *.c
total 64
-rw-rw-r-- 1 vagrant vagrant  1390 Dec  9 15:27 builtins.c
-rw-rw-r-- 1 vagrant vagrant  1138 Dec  9 15:27 env.c
-rw-rw-r-- 1 vagrant vagrant   861 Dec  9 15:27 errors.c
-rw-rw-r-- 1 vagrant vagrant  1035 Dec  9 15:27 execute.c
-rw-rw-r-- 1 vagrant vagrant   232 Dec  9 15:27 free.c
-rw-rw-r-- 1 vagrant vagrant   474 Dec  9 15:27 getline.c
-rw-rw-r-- 1 vagrant vagrant  1387 Dec  9 15:27 helper.c
-rw-rw-r-- 1 vagrant vagrant  1000 Dec  9 15:27 hsh.c
-rw-rw-r-- 1 vagrant vagrant  1004 Dec  9 15:27 path.c
-rw-rw-r-- 1 vagrant vagrant  1019 Dec  9 15:27 shell.h
-rw-rw-r-- 1 vagrant vagrant  1063 Dec  9 15:27 strtok.c
```

