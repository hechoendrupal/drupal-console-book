# generate:command
Cria comandos via console.

**Utilização:**
```
drupal generate:command [options]
gco
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--extension | O nome da extensão.
--extension-type | O tipo da extensão.
--class | Nome da classe do comando
--name | Nome do comando.
--initialize | Add initialize method.
--interact | Add interact method.
--container-aware | Conhece o comando ciente da instalação do site Drupal quando executado
--services | Carrega serviços do container.
--generator | Add a Generator class for this command.

## Exemplos
* Generate a command specifying the extension name and type, its class and the name.
```
drupal generate:command  \
  --extension="ExtensionName"  \
  --extension-type="module"  \
  --class="DefaultCommand"  \
  --name="CommandName"
```
