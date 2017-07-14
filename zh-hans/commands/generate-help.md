# generate:help
生成 hook_help() 的一个实现

**Usage:**
```
drupal generate:help [options]
gh
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--description | 模块说明

## Examples
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
