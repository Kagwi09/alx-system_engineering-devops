0x03-shell_variables_expansions
The alias command is used in Unix-like operating systems (including Linux and macOS) to create shorthand or alternate names for longer or more complex commands. The basic syntax is alias new_command='original_command'

The unalias command is used in Unix-like operating systems (such as Linux and macOS) to remove or disable aliases that you have previously created using the alias command. The basic syntax is unalias alias_name

The source command, also known as the dot command (.), is used in Unix-like operating systems to execute the content of a script or a file within the current shell session. The basic syntx is source filename or . filename

/etc/profile file typically sets environment variables, paths, and system-wide configurations that should be available to all users.The /etc/profile file is executed once for each user session and is responsible for establishing the default environment for all users.

/etc/profile.d/ is a directory where additional scripts can be placed to provide user-specific or system-wide environment customizations

~/.bashrc file is a user-specific configuration file used by the Bash shell, which is a commonly used shell in Unix-like operating systems (such as Linux and macOS). This file allows users to customize their individual shell environment by defining aliases, functions, environment variables, and other shell settings.

Local variables are limited to a specific scope or block and are not accessible outside of that scope.
Global variables are accessible throughout the entire program and can be accessed and modified from anywhere.
Local variables are often used for temporary data and encapsulation, while global variables are used for shared data across different parts of the program.
It's generally considered good practice to use local variables whenever possible to limit unintended interactions and improve code maintainability. Global variables should be used sparingly and only when necessary.

PATH:

Purpose: Defines a list of directories where the shell searches for executable files when you enter a command.
Example: /usr/local/bin:/usr/bin:/bin

HOME:

Purpose: Stores the path to the user's home directory.
Example: /home/username or /Users/username

USER:

Purpose: Holds the username of the currently logged-in user.
Example: username

SHELL:

Purpose: Specifies the path to the user's default shell program.
Example: /bin/bash

PWD:

Purpose: Stores the current working directory.
Example: /home/username

OLDPWD:

Purpose: Stores the previous working directory before changing to a new one.
Example: /home/username/old_directory

PS1:

Purpose: Defines the primary shell prompt, which is displayed at the beginning of the command line.
Example: \u@\h:\w\$

PS2:

Purpose: Defines the secondary shell prompt, used when a command spans multiple lines.
Example: >

LANG and LC_* variables (e.g., LC_ALL, LC_CTYPE, LANG):

Purpose: Determine the localization settings for language, character encoding, and formatting.
Example: en_US.UTF-8

TZ:

Purpose: Sets the time zone for date and time display.
Example: America/New_York

EDITOR:

Purpose: Specifies the default text editor to use for tasks like editing files.
Example: nano or vim

TERM:

Purpose: Defines the type of terminal being used, which helps programs adapt their behavior for different terminal emulations.
Example: xterm or gnome-256color
These are just a few examples of common shell environment variables. They play a crucial role in configuring the behavior of the shell, managing system interactions, and providing user-specific settings

In computing, a child process refers to a process that is created and controlled by another process, known as the parent process. When a parent process creates a child process, the child process is a new instance of a program that inherits certain attributes from the parent process. Child processes can be used to execute tasks concurrently or in a controlled manner.
