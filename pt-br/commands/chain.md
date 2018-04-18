# chain
Execução de comandos em sequência

**Utilização:**
```
drupal chain [arguments] [options]
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--file | Arquivo definido pelo usuário contendo comandos para ser executados em sequência
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
--directory | directory
--language | language

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
command | The command to execute

## Exemplos
* Fornecendo uma opção de arquivo usando o caminho completo.
```
drupal chain \
  --file="/path/to/file/chain-file.yml"
```
