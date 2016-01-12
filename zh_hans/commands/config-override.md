# config:override
**config:override** 命令 覆盖当前使用中的配置值.

**用法:**
```
$ drupal config:override [arguments] 
```

## 可用参数
参数 | 详细
---------|-------------
config-name | 配置名.
key | 键
value | 值

## 例子
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
