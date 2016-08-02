# config:export:view
Export a view in YAML format inside a provided module to reuse in other website.

**使い方:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--module | モジュール名
--optional-config | Export view as an optional YAML configuration in your module
--include-module-dependencies | Include module dependencies in module info YAML file

## 利用可能な引数
引数 | 詳細
---------|-------------
view-id | View ID
