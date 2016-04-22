# yaml:diff
比较两个YAML文件找出区别

**用法:**
```
$ drupal yaml:diff [arguments] [options]
$ yd  
```

## 可用选项
选项 | 详细
-------|-------------
--stats | 打印比较结果
--negate | 定义区别或等同比较,可能值是TRUE/FALSE或0/1
--limit | 限制结果数目
--offset | 起始点

## 可用参数
参数 | 详细
---------|-------------
yaml-left | 用来比较的基础YAML文件
yaml-right | 用来与基础YAML文件比较的YAML文件
