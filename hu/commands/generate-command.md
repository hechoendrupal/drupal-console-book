# generate:command
Parancsok létrehozása a konzolhoz.

**Usage:**
```
drupal generate:command [options]
gco
```

## Available options
Option | Details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | A parancsot leíró osztály. (A 'Command' szóra kell végződnie).
--name | A parancs neve.
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | A parancs ismeri-e a drupal telepítési helyét a végrehajtáskor
--services | Szolgáltatások betöltése a tárolóból.
--generator | Add a Generator class for this command.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
