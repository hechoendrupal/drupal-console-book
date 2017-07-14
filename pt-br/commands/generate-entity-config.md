# generate:entity:config
Gerar uma nova entidade de configuração

**Usage:**
```
drupal generate:entity:config [options]
gec
gecg
```

## Available options
Option | Details
-------|-------------
--module | O nome do módulo.
--entity-class | Classe da entidade de configuração
--entity-name | Nome da entidade de configuração
--base-path | The base-path for the config entity routes
--label | O rótulo
--bundle-of | Atua como um bundle de entidades de conteúdo

## Examples
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
