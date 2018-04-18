# generate:plugin:condition
生成条件插件

**使用方法:**
```
drupal generate:plugin:condition [options]
gpco
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 条件插件类名
--label | 条件插件标签
--plugin-id | 条件插件 ID
--context-definition-id | 上下文定义 ID
--context-definition-label | 上下文定义标签
--context-definition-required | 上下文定义是必须的（TURE 或 FALSE）

## 例子
* Generate a plugin condition for a node entity type specifying the module name, the class, the label, its id and the context definition
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:node"  \
  --context-definition-label="node"  \
  --context-definition-required
```
* Generate a plugin condition for language specifying the module name, the class, the label, its id and the context definition
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="language"  \
  --context-definition-label="Language"  \
  --context-definition-required
```
* Generate a plugin condition for role configuration specifying the module name, the class, the label, its id and the context definition
```
drupal generate:plugin:condition  \
  --module="modulename"  \
  --class="ExampleCondition"  \
  --label="Example condition"  \
  --plugin-id="example_condition"  \
  --context-definition-id="entity:user_role"  \
  --context-definition-label="user_role"  \
  --context-definition-required
```
