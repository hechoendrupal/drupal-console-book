# config:export:single
将单个配置或一系列配置导出为 yml 文件。

**使用方法:**
```
drupal config:export:single [options]
ces
```

## 可用选项
选项 | 详细信息
-------|-------------
--name | commands.config.export.single.options.name
--directory | commands.config.export.arguments.directory
--module | 模块名
--include-dependencies | 导出配置的依赖关系。
--optional | 将配置导出为模块中的可选 YAML 配置
--remove-uuid | 如果设置，配置导出时将没有 uuid 键。
--remove-config-hash | 如果设置，配置导出时将没有默认站点哈希键。

## 例子
* 提供要导出的配置设置名称
```
drupal config:export:single \
  --name=config.settings.name
```
* uuid 和/或配置哈希将被删除。
```
drupal config:export:single \
  --name=config.settings.name \
  --remove-uuid \
  --remove-config-hash
```
