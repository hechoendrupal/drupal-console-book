# generate:command
Génère une commande utilisable via la console

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
--class | Nom de la classe de la commande
--name | Le nom de la commande.
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | Est-ce que la commande est à l'écoute de l'installation drupal lorsqu'elle est exécutée
--services | Charger des services depuis le conteneur.
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
