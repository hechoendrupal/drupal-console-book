# generate:command
The **generate:command** command Generate commands for the console.

**Usage:**
```
$ drupal generate:command [options] 
$ gcm  
```

## Available options
Option | Details
-------|-------------
--module | The Module name.
--class | The Class that describes the command. (Must end with the word 'Command').
--name | The Command name.
--container-aware | Is the command aware of the drupal site installation when executed
