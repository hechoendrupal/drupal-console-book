# generate:entity:content
生成新内容实体

**Usage:**
```
drupal generate:entity:content [options]
geco
gect
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--entity-class | 内容实体类名
--entity-name | 内容实体名称
--base-path | 内容实体路由的基本路径
--label | 标签
--has-bundles | 实体包含 Bundles
--is-translatable | 内容实体可翻译
--revisionable | commands.generate.entity.content.options.revisionable

## Examples
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
