# chain
Chain parancs végrehajtása

**Használat:**
```
$ drupal chain [arguments] [options]
```

## Rendelkezésre álló beállítások
Beállítás | Részletek
-------|-------------
--file | A végrehajtandó parancsokat tartalmazó, felhasználó által megadott fájl.
--placeholder | commands.chain.options.placeholder
--help | Display this help message
--quiet | Suppress all output from the command
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output, and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--no-debug | Switches off debug mode
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## Rendelkezésre álló argumentumok
Argumentum | Részletek
---------|-------------
command | The command to execute
