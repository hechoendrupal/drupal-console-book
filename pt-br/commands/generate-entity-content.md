# generate:entity:content
Gerar uma nova entidade de conteúdo

**Utilização:**
```
drupal generate:entity:content [options]
geco
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--entity-class | Classe da entidade de conteúdo
--entity-name | Nome da entidade de conteúdo
--base-path | The base-path for the content entity routes
--label | O rótulo
--has-bundles | A entidade tem bundles
--is-translatable | Content entity translatable
--revisionable | commands.generate.entity.content.options.revisionable

## Exemplos
* Generate a content entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
* Generate a translatable and revisionable content entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:content  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"  \
  --is-translatable  \
  --revisionable
```
