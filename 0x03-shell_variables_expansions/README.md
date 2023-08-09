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


