# generate:doc:gitbook
The **generate:doc:gitbook** command Generate documentations for Commands

**Usage:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## Available options
Option | Details
-------|-------------
--path | The path to render the documentation
--learning | Генерация подробного вывода
--help | Показать эту подсказку
--quiet | Не показывать никаких сообщений
--verbose | Увеличение подробности вывода: 1 - стандартный вывод, 2 - более подробный вывод и 3 - отладочный вывод
--version | Показать версию этого приложения
--ansi | Принудительный ANSI вывод
--no-ansi | Отключить ANSI вывод
--no-interaction | Не задавать никакие интерактивные вопросы
--env | Имя среды окружения
--root | Указать корневую директорию Drupal для выполнения команд
--no-debug | Выключение режима отладки
--generate-chain | Показывает парамметры и аргументы выполняемой команды как yaml вывод для передачи по цепочке
--generate-inline | Показывает парамметры и аргументы выполняемой команды одной строкой
--generate-doc | Показывает парамметры и аргументы выполняемой команды как markdown
--target | Имя сайта, с которым вы хотите взаимодействовать (для локального или удаленного сайтов)
--uri | URI сайта Drupal (в случае мультисайтингового окружения или запуска на альтернативном порту)
--yes | Пропустить подтверждение и продолжить

## Available arguments
Argument | Details
---------|-------------
command | Команда на выполнение
