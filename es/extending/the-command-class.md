# La clase Command

Los comandos personalizados deben extender cualquiera de las clases base provistas por el el proyecto DrupalConsole Core.

## Extendiendo la clase base `Command`

Extendiendo la clase base `Command`, su comando será capaz de utilizar la característica de multilenguaje provista por DrupalConsole.

1.- Importe la clase `Command`.
```
use Drupal\Console\Core\Command\Command;
```

2.- Extienda la clase importada `Command`.
```
class DefaultCommand extends Command
```

## Extendiendo la clase `ContainerAwareCommand`.

Para tener acceso al contendedor de servicios, extendienda la clase `ContainerAwareCommand` en su clase (en lugar de `Command`, que es más básica).

En otras palabras, puede acceder a cualquier servicio Drupal configurado usando el método `get`.

1.- Importe la clase `ContainerAwareCommand`.
```
use Drupal\Console\Core\Command\ContainerAwareCommand;
```

2.- Extienda la clase importada `ContainerAwareCommand`.
```
class DefaultCommand extends ContainerAwareCommand
```
