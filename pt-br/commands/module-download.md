# module:download
Download module or modules in application

**Utilização:**
```
drupal module:download [arguments] [options]
mod
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--path | The path of the contrib project
--latest | Default to download most recent version
--composer | Download the module using Composer
--unstable | Module unstable

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
module | Module or modules to be enabled should be separated by a space

## Exemplos
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
