# config:export:view
Export 1 view trong YAML format inside 1 module được cung cấp để sử dụng lại trên các website khác.

**application.gitbook.messages.usage:**
```
drupal config:export:view [arguments] [options]
cev
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Tên module.
--optional-config | Export view như một lựa chọn YAML configuration trong module của bạn
--include-module-dependencies | Bao gồm module dependencies trong module info YAML file

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
view-id | View ID

## application.gitbook.messages.examples
* Provide a view id
```
drupal config:export:view viewid
```
* You can provide the interactive values like parameter.
```
drupal config:export:view viewid \
  --module="modulename" \
  --optional-config \
  --include-module-dependencies
```
