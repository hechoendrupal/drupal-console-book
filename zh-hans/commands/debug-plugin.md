# debug:plugin
显示所有插件类型。

**使用方法:**
```
drupal debug:plugin [arguments]
dpl
```

## 可用参数
参数 | 详细信息
---------|-------------
type | 插件类型
id | 插件 ID

## 例子
* 显示当前站点上所有插件的列表
```
drupal debug:plugin
```
* 显示区块插件信息
```
drupal debug:plugin block
```
* 显示区块损坏信息
```
drupal debug:plugin block broken
```
