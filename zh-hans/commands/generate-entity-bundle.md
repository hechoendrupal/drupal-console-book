# generate:entity:bundle
生成新内容类型（node 或实体 bundle）

**Usage:**
```
drupal generate:entity:bundle [options]
geb
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--bundle-name | 内容类型的机读名称
--bundle-title | 内容类型的名称

## Examples
* Generate bundle entity specifying the module, the bundle name and its title
```
drupal generate:entity:bundle  \
  --module="modulename"  \
  --bundle-name="default"  \
  --bundle-title="default"
```
