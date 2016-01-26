# Command Lifecycle
 
Commands have three lifecycle methods:

## The initialize method (optional)
This method is executed before the `interact` and `execute` methods. 
Its main purpose is to initialize variables used in the rest of the command methods.

## The interact method (optional)
This method is executed after `initialize` and before `execute` methods. 
Its purpose is to check if some of the options/arguments are missing and interactively ask the user for those values. This is the last place where you can ask for missing options/arguments. After this command, missing options/arguments will result in an error.

## The execute method (required)
This method is executed after `interact` and `initialize` methods. 
It contains the logic you want the command to execute.
