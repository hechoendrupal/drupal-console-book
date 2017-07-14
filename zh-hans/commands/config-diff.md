# config:diff
输出选取目录中和使用中不同的配置项目.

**Usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## Available options
Option | Details
-------|-------------
--reverse | 反向显示差异(就是说：从一个目录到使用配置的比较).

## Available arguments
Argument | Details
---------|-------------
directory | 要对比的目录. 缺省使用配置目录.

## Examples
* Provide a config directory
```
drupal config:diff ../config/path
```
