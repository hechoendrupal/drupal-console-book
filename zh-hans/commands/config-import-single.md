# config:import:single
导入单个配置或一系列配置。

**使用方法:**
```
drupal config:import:single [options]
cis
```

## 可用选项
选项 | 详细信息
-------|-------------
--file | 要导入的文件名或文件绝对路径
--directory | commands.config.import.arguments.directory

## 例子
* 使用完整路径提供文件选项。
```
drupal config:import:single \
  --file="/path/to/file/block.block.default_block.yml"
```
* 提供文件和目录选项
```
drupal config:import:single  \
  --file="block.block.default_block.yml" \
  --directory="/path/to/directory"
```
