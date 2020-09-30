# Unix course – Introduction to basic Unix commands

On Unix, every user has a unique user name. When they log on to the system, they are placed in a home directory, which is a portion of the disk space reserved just for them. When you log onto a Unix system, your main interface to the system is  called the Unix Shell. This is the program that presents you with the dollar sign (`$`) prompt. This prompt means that the shell is ready to accept your typed commands.

Unix commands are strings of characters typed in at the keyboard. To  run a command, you just type it in and press the *Enter* key. We will look at several of the most common commands below. 

Unix extends the power of commands by using special flags or *switches*. Switches are usually preceded with a dash (`-`).

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
| `..`                | parent directory                                             |
| `.`                 | current directory                                            |
| `*`                 | wildcard representing any combination of characters          |
| `~`                 | your home directory                                          |
| `>`                 | send output to a file                                        |
| `>>`                | append (add) output to a file                                |
| `\|`                 | pipe output from one command as input to another             |

## Tutorial

Our main objective for this tutorial is

<details><summary>Show solution</summary><pre><code>
rm -r mydir
</code></pre></details>