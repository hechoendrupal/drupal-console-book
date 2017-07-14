# generate:command
Generate commands for the console.

**Usage:**
```
drupal generate:command [options]
gco
```

## Available options
Option | Details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | The Class that describes the command. (Must end with the word 'Command').
--name | The Command name.
--container-aware | Is the command aware of the drupal site installation when executed
--services | Load services from the container.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
