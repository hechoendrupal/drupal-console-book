# generate:command
Generar comandaments per la consola

**Ús:**
```
drupal generate:command [options]
gco
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--extension | The extension name.
--extension-type | The extension type.
--class | La Classe que descriu el comandament. (Ha d'acabar amb la paraula 'Commmand').
--name | Nom del comandament.
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | Es el comandament conscient de l'instal·lació de Drupal quan s'executa
--services | Carregar serveis des del contenidor.
--generator | Add a Generator class for this command.

## Exemples
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
