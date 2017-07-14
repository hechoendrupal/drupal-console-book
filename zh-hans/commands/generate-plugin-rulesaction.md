# generate:plugin:rulesaction
生成一个规则（Rule）行为（action）插件

**Usage:**
```
drupal generate:plugin:rulesaction [options]
gpra
```

## Available options
Option | Details
-------|-------------
--module | 模块名称
--class | 插件类名
--label | 插件标签
--plugin-id | 插件id
--type | 行为类别 (用户 or 节点)
--category | 插件类别
--context | 插件上下文

## Examples
* Generate a user rule action plugin specifying the module name, the class, its label, the plugin id, the type, the category and its context
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="user"  \
  --category="default_action"  \
  --context="default_action"
```
* Generate a node rule action plugin specifying the module name, the class, its label, the plugin id, the type, the category and its context
```
drupal generate:plugin:rulesaction  \
  --module="modulename"  \
  --class="DefaultAction"  \
  --label="Default action"  \
  --plugin-id="default_action"  \
  --type="node"  \
  --category="default_action" \
  --context="default_action"
```
