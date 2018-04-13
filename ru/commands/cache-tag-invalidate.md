# cache:tag:invalidate
Invalidate cache tags.

**Использование:**
```
drupal cache:tag:invalidate [arguments]
cti
```

## Доступные аргументы
Аргумент | Детали
---------|-------------
tag | One or more tags to invalidate.

## Примеры
* Invalidate routes
```
drupal cti routes
```
* Invalidate a specific node
```
drupal cti node:1 node_list
```
