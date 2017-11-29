# Автоматическая регистрация команд

Чтобы команды командной строки были доступны автоматически внутри Drupal инсталляции вам необходимо:

* Создать каталог `Command` внутри вашего модуля, например `src/Command`, и создать файл `PHP` с суффиксом `Command.php`, например `MyCustomCommand.php`, для каждой вашей команды.

* Убедитесь, что вы наследуете класс `Command` или `ContainerAwareCommand`.

Drupal Console предоставляет два типа команд: `stand alone` и `container aware`.

## Автономные команды
Эти команды выводятся и могут быть запущены вне Drupal инсталляции, вы можете определить ее, унаследовав класс `Command`.
```
use Drupal\Console\Command\Command;

class MyStandAloneCommand extends Command
{
}
```
 
## Команды зависящие от контейнера
Такие команды выводятся и могут быть запущены только внутри Drupal инсталляции, вы можете определить ее, унаследовав класс  `ContainerAwareCommand`.
```
use Drupal\Console\Command\ContainerAwareCommand;

class MyContainerAwareCommand extends ContainerAwareCommand
{
}
```
