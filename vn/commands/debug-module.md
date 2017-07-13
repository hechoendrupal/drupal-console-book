# debug:module
Hiển thị các module hiện có cho ứng dụng

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal debug:module [arguments] [options]
$ dm  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--status | Trạng thái module [enabled|disabled]
--type | Loại Module [core|no-core]

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
module | Module name

## commands.generate.doc.gitbook.messages.examples
* Display all installed modules
```
$ drupal mod --status=installed
```
* Display all installed and no core modules
```
$ drupal mod --status=installed --type=no-core
```
