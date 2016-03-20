# Registrando Comandos Automáticamente

Para hacer que comandos para la Drupal Console estés disponibles automáticamente dentro de tu instalación de Drupal, necesitarás:

* Crear un directorio `Command` dentro de tu módulo i.e. `src/Command` y crear un archivo `PHP` con la terminación `Command.php` i.e. `MyCustomCommand.php` para cada comando que quieras proveer.

* Asegúrate que tu clase extienda una de las siguientes clases: `Command` o `ContainerAwareCommand`.

Drupal Console provee dos tipos de comandos: `autónomos` y `conscientes del contenedor`.

## Comandos autónomos
Estos comandos son listados y pueden ejecutarse fuera de una instalación de Drupal. Se crean extendiendo la clase `Command`.
```
use Drupal\Console\Command\Command;

class MyStandAloneCommand extends Command
{
}
```
 
## Comandos conscientes del contenedor
Estos comandos son listados y deben ejecutarse dentro de una instalación de Drupal. Se crean extendiendo la clase `ContainerAwareCommand` class.
```
use Drupal\Console\Command\ContainerAwareCommand;

class MyContainerAwareCommand extends ContainerAwareCommand
{
}
```
