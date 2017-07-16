# Creating Custom Commands

The easiest way to create a custom Command Class is to execute the `generate:command` command.

Executing the command using the interactive command questions: 
```
 // Welcome to the Drupal Command generator
 Enter the extension name [config_update]:
 > example

 Enter the Command name. [example:default]:
 >

 Enter the Command Class. (Must end with the word 'Command'). [DefaultCommand]:
 >

 Is the command aware of the drupal site installation when executed?. (yes/no) [no]:
 >

 Do you want to load services from the container (yes/no) [no]:
 > yes

Type the service name or use keyup or keydown.
This is optional, press enter to continue

 Enter your service [ ]:
 > entity_type.manager
 Enter your service [ ]:
 >

 Do you confirm generation? (yes/no) [yes]:
 >

Generated or updated files

 1 - modules/custom/example/src/Command/DefaultCommand.php
 2 - modules/custom/example/console.services.yml
 3 - modules/custom/example/console/translations/en/example.default.yml
```

Executing the `generate:command` passing inline options, make sure you adjust the following command based on your requirements.
```
drupal generate:command \
--extension="example" \
--extension-type="module" \
--class="DefaultCommand" \
--name="example:default" \
--services='entity_type.manager' \
--no-interaction
```

This command execution will generate a new Command class and the service registration containing the boiler-plate required to register a new command.
