# generate:event:subscriber
Generate an event subscriber

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | モジュール名
--name | Service name
--class | Class name
--events | コンテナからイベントを読み込む
--services | コンテナからサービスを読み込む

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
