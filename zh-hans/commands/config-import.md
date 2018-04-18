# config:import
将配置导入当前应用程序。

**使用方法:**
```
drupal config:import [options]
ci
```

## 可用选项
选项 | 详细信息
-------|-------------
--file | 要导入的配置的归档文件的路径。
--directory | 要导入的配置目录的路径。
--remove-files | 同步后删除文件。
--skip-uuid | commands.config.import.options.skip-uuid

## 例子
* 提供一个配置文件
```
drupal config:import \
  --file=/path/to/config/file
```
* 提供配置目录
```
drupal config:import  \
  --directory=/path/to/config/dir
```
