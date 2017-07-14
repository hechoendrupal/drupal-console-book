# generate:command
Generează comenzi pentru consolă.

**Usage:**
```
drupal generate:command [options]
gco
gcm
```

## Available options
Option | Details
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | Numele Clasei "Command"
--name | Numele comenzii.
--container-aware | Când este executată comanda este conștientă de instalarea de drupal a sitului
--services | Încarcă serviciile din container.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
