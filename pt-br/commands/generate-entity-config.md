# generate:entity:config
Gerar uma nova entidade de configuração

**Utilização:**
```
drupal generate:entity:config [options]
gec
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--entity-class | Classe da entidade de configuração
--entity-name | Nome da entidade de configuração
--base-path | The base-path for the config entity routes
--label | O rótulo
--bundle-of | Atua como um bundle de entidades de conteúdo

## Exemplos
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
