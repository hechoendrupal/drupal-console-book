# Registering Commands Automatically

To make the console commands available automatically within a Drupal installation, you will need to:

* Create a `Command` directory inside your module i.e. `src/Command` and create a `PHP` file suffixed with `Command.php` i.e. `MyCustomCommand.php` for each command that you want to provide.

* Make sure you class extends one of `Command` or `ContainerAwareCommand` classes.

Drupal Console provides two types of commands, `stand alone` and `container aware` commands.

## Stand alone commands
These commands are listed and can run outside of a Drupal installation, you defined one by extending the `Command` class.
```
use Drupal\Console\Command\Command;

class MyStandAloneCommand extends Command
{
}
```
 
## Container aware commands
These commands are listed and must be run against a Drupal, you defined one by extending the `ContainerAwareCommand` class.
```
use Drupal\Console\Command\ContainerAwareCommand;

class MyContainerAwareCommand extends ContainerAwareCommand
{
}
```
