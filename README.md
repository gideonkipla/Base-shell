**PID and PPDI Shell**

**This is a shell written in c language to resemble the sh shell in ubuntu**

Write a beautiful code that passes the Betty checks
Write a UNIX command line interpreter.
Simple shell 0.1 + Handle command lines with arguments
Simple shell 0.2 + Handle the PATH. fork must not be called if the command doesn’t exist
Simple shell 0.3 + Implement the exit built-in, that exits the shell. Usage: exit. You don’t have to handle any argument to the built-in exit
Simple shell 0.4 + Implement the env built-in, that prints the current environment
Simple shell 0.1 + Write your own getline function. Use a buffer to read many chars at once and call the least possible the read system call. You will need to use static variables
Simple shell 0.2 + You are not allowed to use strtok
Simple shell 0.4 + handle arguments for the built-in exit. Usage: exit status, where status is an integer used to exit the shell
Simple shell 1.0 + Implement the setenv and unsetenv builtin commands. setenv. Initialize a new environment variable, or modify an existing one. Command syntax: setenv VARIABLE VALUE. Should print something on stderr on failure. unsetenv. Remove an environment variable. Command syntax: unsetenv VARIABLE. Should print something on stderr on failure
Simple shell 1.0 + Implement the builtin command cd:. Changes the current directory of the process. If no argument is given to cd the command must be interpreted like cd $HOME. You have to handle the command cd -. You have to update the environment variable PWD when you change directory. man chdir, man getcwd
Simple shell 1.0 + Handle the commands separator ;
Simple shell 1.0 + Handle the && and || shell logical operators
Simple shell 1.0 + Implement the alias builtin command. Usage: alias [name[='value'] ...]
Simple shell 1.0 + Handle variables replacement. Handle the $? variable. Handle the $$ variable
Simple shell 1.0 + Handle comments (#)
Simple shell 1.0 + Usage: simple_shell [filename]. Your shell can take a file as a command line argument. The file contains all the commands that your shell should run before exiting. The file should contain one command per line
