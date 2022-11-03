Name: Shell
Status: published

## Description

Shells are command interpreters adopted by [Unix-like](https://en.wikipedia.org/wiki/Unix-like) operating systems. The shell is the program that runs in your terminal when you log in. It allows you to execute other programs, handles I/O redirection, performs various expansions, and so on. Shell commands can be run interactively in the terminal or they can be put in a file and run as a script. Although the shell is a programming language with constructs like `if` and `while`, it's primary goal is to run, control, and glue together other programs.

The term shell and the idea of a program running other programs was introduced by Louis Pouzin for the [Multics](https://en.wikipedia.org/wiki/Multics) operating system in 1964. In 1971, Ken Thompson implemented the first Unix shell known as the [Thompson shell](https://en.wikipedia.org/wiki/Thompson_shell) (`sh`) that came with the very first version of Unix. In 1979, it was replaced by the Bourne shell (`sh`). Another influential shell is the [C shell](https://en.wikipedia.org/wiki/C_shell) (`csh`) that found its way in the BSD version of Unix in the late 1970s. Different incompatible shells started to arise, so [POSIX](https://en.wikipedia.org/wiki/POSIX) defined features that should be common to all Unix shells. A subset of the [Korn shell](https://en.wikipedia.org/wiki/KornShell) (`ksh`) was used as a basis for the standard. [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) (`bash`) is a shell for the [GNU Project](https://en.wikipedia.org/wiki/GNU_Project "GNU Project"). It's a default interactive shell on most Linux distributions. Some Linux distributions use [Dash](https://en.wikipedia.org/wiki/Almquist_shell#dash) (`dash`) as a scripting shell. While `bash` extends POSIX, `dash` tries to be as minimal as possible to conform to the standard. The [Z shell](https://en.wikipedia.org/wiki/Z_shell) (`zsh`) is another popular shell, which is default on macOS since Catalina.

`bash` is the most popular shell for scripting because it's so widely available. But since `bash` is not guaranteed to be present on any Unix-like system, it's a common practice to write scripts using only features defined by POSIX. Which interactive shell to use is more of a matter of personal taste. Both `bash` and `zsh` are popular. You may also like [`fish`](https://en.wikipedia.org/wiki/Fish_(Unix_shell)).

Shell scripting has many quirks and legacy features. It's more and more common to see shell scripting being replaced with languages like Python. Nevertheless, shell scripts are not going to go anywhere. They work well for invoking other commands and can be executed almost anywhere.

Links: [Unix shell (Wikipedia)](https://en.wikipedia.org/wiki/Unix_shell), [Comparison of command shells (Wikipedia)](https://en.wikipedia.org/wiki/Comparison_of_command_shells), [List of Unix commands (Wikipedia)](https://en.wikipedia.org/wiki/List_of_Unix_commands), [The Origin of the Shell](https://multicians.org/shell.html), [POSIX Shell & Utilities](https://pubs.opengroup.org/onlinepubs/9699919799/), [ShellCheck](https://github.com/koalaman/shellcheck), [explainshell.com](https://explainshell.com/).

## Resources

[POSIX Shell & Utilities](https://pubs.opengroup.org/onlinepubs/9699919799/)
free • resource • 2018-01-01
This is a POSIX volume that defines the Shell Command Language and utilities that should be present on a Unix system. You won't learn the shell by reading the standard, but the language definition is quite short and readable to be worth checking out. It's the ultimate source of truth on what POSIX shell is and is not.

[Bash Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
free • resource
The Bash official manual is a great resource that is worth reading from cover-to-cover. It has an advantage of being always at hand with `man bash`.

[GNU Coreutils Manual](https://www.gnu.org/software/coreutils/manual/coreutils.html)
free • resource
GNU Coreutils is an implementation of Unix utilities for GNU/Linux distributions. The manual is a nicely structured and detailed description of all the available shell commands. If you want to enlarge your shell vocabulary, this is a perfect resource.

[Greg's Wiki](https://mywiki.wooledge.org/EnglishFrontPage)
free • resource
This is an indispensable resource for anyone doing shell programming. [BashFAQ](https://mywiki.wooledge.org/BashFAQ) tells how to do certain things in Bash, and [BashPitfalls](https://mywiki.wooledge.org/BashPitfalls) tells what to avoid. [BashSheet](https://mywiki.wooledge.org/BashSheet) condenses all of the Bash syntax and features on a small page. [BashGuide](https://mywiki.wooledge.org/BashGuide) is the best introduction to Bash with lots of examples and practical advice. Although the wiki is devoted to Bash, there is the [Bashism](https://mywiki.wooledge.org/Bashism) page that summarizes Bash-specific features.
