# cache:tag:invalidate
Invalidate cache tags.

**Usage:**
```
drupal cache:tag:invalidate [arguments]
cti
```

## Available arguments
Argument | Details
---------|-------------
tag | One or more tags to invalidate.

## Examples
* Invalidate routes
```
drupal cti routes
```
* Invalidate a specific node
```
drupal cti node:1 node_list
```
