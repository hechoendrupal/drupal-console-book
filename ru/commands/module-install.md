# module:install
Устанавливает модуль или модули в приложении

**Использование:**
```
drupal module:install [arguments] [options]
moi
```

## Доступные параметры
Команда | Детали
-------|-------------
--latest | По умолчанию скачивать последнюю версию
--composer | Удаляет модули, используя Composer
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

## Доступные аргументы
Аргумент | Детали
---------|-------------
command | The command to execute
module | Модуль или модули, которые будут активированы должны быть разделены пробелами

## Примеры
* Установка указанного модуля
```
drupal module:install  modulename
```
