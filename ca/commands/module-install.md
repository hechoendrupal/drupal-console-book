# module:install
Instal·lar mòdul en l'aplicació

**Ús:**
```
drupal module:install [arguments] [options]
moi
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--latest | Descarregar la versió més actual de forma predeterminada
--composer | Uninstalls the module using Composer
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

## Arguments disponibles
Argument | Detalls
---------|-------------
command | The command to execute
module | Mòduls per habilitar separats per un espai

## Exemples
* Install module specifying the module name
```
drupal module:install  modulename
```
