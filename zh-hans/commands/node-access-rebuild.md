# node:access:rebuild
创建节点访问权限. 重建会移除所有内容上的使用权限并替换为当前模块或当前设置里的权限

**使用方法:**
```
drupal node:access:rebuild [options]
nar
```

## 可用选项
选项 | 详细信息
-------|-------------
--batch | 批量模式处理

## 例子
* 创建节点访问权限
```
drupal node:access:rebuild --batch
```
