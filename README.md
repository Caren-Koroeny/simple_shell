# 0x16. C - Simple Shell

* In this repository you will find the entire project where we built our own version of a Shell.

# Resources.

## Read or watch:

  * [Unix shell](https://en.wikipedia.org/wiki/Unix_shell)

  * [Thompson shell](https://en.wikipedia.org/wiki/Thompson_shell)

  * [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson)

  * [Everything you need to know to start coding your own shell](https://alx-intranet.hbtn.io/concepts/64)

## Additional materials:

  * [Tutorial - Write a Shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/)
  
  * [How Does the Shell Command ls Work](https://medium.com/@bdov_/what-happens-when-you-type-ls-c-in-the-shell-93327856ee9c)

## Learning Objectives :bulb:

What you should learn from this project:

   * Who designed and implemented the original Unix operating system
 
   * What are the three prototypes of main.

   * How does the shell use the PATH to find the programs.

   * How to execute another program with the execve system call.

   * How to suspend the execution of a process until one of its children terminates.

   * What is EOF / “end-of-file”?

# Tasks :hammer_and_pick:

* [README, man, AUTHORS](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Write a README, Write a man for your shell. You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository.

* [0. Betty would be proud](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Write a beautiful code that passes the Betty checks.

* [1. Simple shell 0.1](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Write a UNIX command line interpreter.

* [2. Simple shell 0.2](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Handle command lines with arguments.

* [3. Simple shell 0.3](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Handle the `PATH`

   * `fork` must not be called if the command doesn’t exist.

* [4. Simple shell 0.4](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Implement the exit built-in, that `exits` the shell

   * Usage: `exit`

   * You don’t have to handle any argument to the `built-in exit`

* [5.Simple shell 1.0](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Implement the `env built-in`, that prints the current environment.

* [6.Simple shell 0.1.1](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Write your own `getline` function

   * Use a `buffer` to read many chars at once and call the least possible the read system call

   * You will need to use `static` variables

   * You are not allowed to use `getline`

* [7. Simple shell 0.2.1](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * You are not allowed to use `strtok`

* [8. Simple shell 0.4.1](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * handle arguments for the built-in `exit`

   * Usage: `exit status`, where status is an integer used to exit the `shell`

* [9. setenv, unsetenv](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * **setenv**

    - Initialize a new environment variable, or modify an existing one

    - Command syntax: `setenv` VARIABLE VALUE

    - Should print something on `stderr` on failure.

   * **unsetenv**
 
    - Remove an environment variable.

    - Command syntax: `unsetenv VARIABLE`.

    - Should print something on `stderr` on failure

* [10. cd](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Implement the builtin command cd:

    - Changes the `current directory` of the process.

    - Command syntax: `cd [DIRECTORY]`

    - If no argument is given to `cd` the command must be interpreted like `cd $HOME`

    - You have to handle the command `cd -`

    - You have to update the environment variable `PWD` when you change directory.

    - `man chdir, man getcwd`

* [11. ;](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Handle the commands separator `;`

* [12. && and ||](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Handle the `&&` and `||` shell logical operators.

* [13. alias](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Implement the `alias` builtin command

* [14. Variables](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Handle variables replacement - Handle the `$?` variable - Handle the `$$` variable.

* [15. Comments](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Handle comments `(#)`

* [16. File as input](https://github.com/Caren-Koroeny/simple_shell/blob/master/hsh.c)

   * Your shell can take a file as a command line argument.

## Authorblack:  :black_nib:

* Caren Siya 

   * [Github](https://github.com/Caren-Koroeny)

   * [Twitter](https://twitter.com/home)

   * [Linkedin](https://www.linkedin.com/in/caren-siya-a89712180/)

* Brian Kipngeno.

   * [Github](https://github.com/yobwee-zy)

   * [Email](bkingeno07@gmail.com)

   * [Linkedin]( https://www.linkedin.com/in/brian-kipngeno-104897232) 


