# generate:plugin:migrate:process
Generate a migrate process plugin

**使用方法:**
```
drupal generate:plugin:migrate:process [options]
gpmp
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | Plugin class name
--plugin-id | Plugin id

## 例子
* Generate a migration plugin process specifying the module name, the class and its id
```
drupal generate:plugin:migrate:process  \
  --module="modulename"  \
  --class="MigrationProcess"  \
  --plugin-id="migrationprocess"
```
