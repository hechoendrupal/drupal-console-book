# Creating Custom Commands

The simple way to create a custom Command Class is to execute the `generate:command` command.

Executing the command using the interactive command questions: 
```
 $ drupal generate:command
 
 // Welcome to the Drupal Command generator
 Enter the module name [devel]:
 > example

 Enter the Command name. [example:default]:
 >

 Enter the Command Class. (Must end with the word 'Command'). [DefaultCommand]:
 >

 Is the command aware of the drupal site installation when executed?. (yes/no) [yes]:
 >

 Do you confirm generation? (yes/no) [yes]:
 >

Generated or updated files
 Site path: /var/www/drupal.dev
 1 - modules/custom/example/src/Command/DefaultCommand.php
```

Executing the `generate:command` passing inline options, make sure you adjust the following command based on your requirements.

```
$ drupal generate:command  --module=example --class=DefaultCommand --name=example:default --container-aware -y
```

This command execution will generate a new Command class containing the boiler-plate required to register a new command within your Drupal module.
