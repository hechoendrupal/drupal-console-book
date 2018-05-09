# module:download
Descarregar mòduls a la aplicació

**Ús:**
```
drupal module:download [arguments] [options]
mod
```

## Opcions disponibles
Opció | Detalls
-------|-------------
--path | The path of the contrib project
--latest | Descarregar la versió més actual de forma predeterminada
--composer | Download the module using Composer
--unstable | Module unstable

## Arguments disponibles
Argument | Detalls
---------|-------------
module | Mòduls per habilitar separats per un espai

## Exemples
* Download module specifying module name and its path
```
drupal module:download  modulename  \
  --path="modules/contrib"
```
