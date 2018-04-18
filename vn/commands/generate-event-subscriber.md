# generate:event:subscriber
Tạo một event subscriber

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | Tên module.
--name | Service name
--class | Class name
--events | Nạp các sự kiện từ container
--services | Nạp các dịch vụ từ container.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
