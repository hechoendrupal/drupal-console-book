# config:export
导出当前应用配置。

**使用方法:**
```
drupal config:export [options]
ce
```

## 可用选项
选项 | 详细信息
-------|-------------
--directory | 定义导出目录以保存配置输出。
--tar | 如果设置，配置将导出到归档文件。
--remove-uuid | 如果设置，配置导出时将没有 uuid 键。
--remove-config-hash | 如果设置，配置导出时将没有默认站点哈希键。

## 例子
* 您可以选择添加要导出的路径
```
drupal config:export  \
  --directory="path/to/export"
```
* 导出的配置到压缩文件中，并且 uuid 和配置哈希将被删除。
```
drupal config:export  \
  --directory="path/to/export" \
  --tar \
  --remove-uuid \
  --remove-config-hash
```
