# Simple Shell
## Project details
Welcome to the **Simple Shell** project!! This program is a simple shell that can be compiled and launched from the command line.

## How to Compile
> gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh

## Syntax
When using this shell, the syntax for running any command follows the familiar syntax when running a command in any other shell.


## Testing
After the compilation, you can execute is interactive mode:
```
$ ./hsh
$ /bin/ls
hsh main.c shell.c
$
$ exit
```

But also in non-interactive mode:
```
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2
$
$ cat test_ls_2
/bin/ls
/bin/ls
$
```

# Authors
[Jude Adesulu](https://github.com/jude-adesulu) & [Patrick Akuagwu](https://github.com/patrick-akuagwu)
