# generate:help
生成 hook_help() 的一个实现

**使用方法:**
```
drupal generate:help [options]
gh
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--description | commands.generate.help.options.description

## 例子
* Generate a hook help specifying the module name and the description
```
drupal generate:help  \
  --module="modulename"  \
  --description="My Awesome Module"
```
