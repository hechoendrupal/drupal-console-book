# settings:set
Change a specific setting value in DrupalConsole config file

**Utilização:**
```
drupal settings:set [arguments] [options]
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--debug | Switches on debug mode
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
command | The command to execute
name | Setting name in YAML flatten format to set a value in Drupal Console config file
value | Setting value to set in Drupal Console config file

## Exemplos
* Set application language setting value to "es"
```
drupal settings:set  application.language es
```
