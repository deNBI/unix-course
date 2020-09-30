# Unix course – Introduction to basic Unix commands

On Unix, every user has a unique user name. When they log on to the system, they are placed in a home directory, which is a portion of the disk space reserved just for them. When you log onto a Unix system, your main interface to the system is  called the Unix Shell. This is the program that presents you with the dollar sign (`$`) prompt. This prompt means that the shell is ready to accept your typed commands.

Unix commands are strings of characters typed in at the keyboard. To  run a command, you just type it in and press the *Enter* key. We will look at several of the most common commands below. 

Unix extends the power of commands by using special flags or *switches*. Switches are usually preceded with a dash (`-`).

TODO: explain command parameters e.g. `cd first_analysis`

## List of commands

| Command             | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| `pwd`               | print working (current) directory                            |
| `ls`                | list contents of the current directory                       |
| &#10551; `-l`       | long (detailed) listing                                      |
| `cd`                | change to another directory                                  |
| `mkdir`             | make a new directory                                         |
| `mv`                | move or rename a file or directory                           |
| `cp`                | copy file                                                    |
| &#10551; `-r`       | copy directory tree                                          |
| `echo`              | display a line of text                                       |
| `less`              | display contents of a file                                   |
| `grep`              | list text lines containing particular characters             |
| `cat`               | concatenate (combine) two or more files                      |
| `df`                | show disk free information                                   |
| `find`              | find files in a directory tree                               |
| `man`               | display program manual for a command                         |
| `ps aux`            | display status of all processes (running programs)           |
| `kill`              | kill process                                                 |
| &#10551; `-9`       | kill process immediately                                     |
| `rm`                | remove a file                                                |
| &#10551; `-r`       | remove a directory tree                                      |
| `rmdir`             | remove an empty directory                                    |
| `chmod`             | change mode (security permissions) of file or directory      |
| &#10551; `ugo+-rwx` | user (owner), group, other (world), add, remove, read, write, execute |
| `*`                 | wildcard representing any combination of characters          |
| **Places** |  |
| `~`                 | your home directory                                          |
| `.`                 | current directory                                            |
| `..`                | parent directory                                             |
| **Pipes** |  |
| `>`                 | send output to a file                                        |
| `>>`                | append (add) output to a file                                |
| `\|`                 | pipe output from one command as input to another             |

## Tutorial

During this tutorial you will use the commands above to run some basic bioinformatic analyses.
Your task is to identify the correct commands and execute them. Feel free to experiment. Take a look at the solutions if necessary.

### 01 - Accessing the Virtual Machine

TODO

### 02 - Opening a terminal window

TODO

### 03 - Creating a directory to work in

1. Please find out your current directory. (1 command)
2. If your current directory is not your home directory, please move to it. (1 command)
3. Now create a directory called `first_analysis` and enter the new directory. (2 commands)

<details><summary>Show solution</summary><pre><code>
pwd
cd ~
mkdir first_analysis
cd first_analysis
</code></pre></details>

### 04 - 





TODO: create Go binary that calculates PI

TODO: user copies binary from shared dir to home, inspects it (`file`), makes it executable, runs it, pipes output to file, inspects file, ...