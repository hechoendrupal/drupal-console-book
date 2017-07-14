# generate:command
Cria comandos via console.

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
--class | Nome da classe do comando
--name | Nome do comando.
--container-aware | Conhece o comando ciente da instalação do site Drupal quando executado
--services | Carrega serviços do container.

## Examples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
