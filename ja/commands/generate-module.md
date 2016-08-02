# generate:module
Generate a module.

**使い方:**
```
$ drupal generate:module [options]
$ gm  
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--module | The Module name
--machine-name | The machine name (lowercase and underscore only)
--module-path | The path of the module
--description | Module description
--core | Core version
--package | Module package
--module-file | Add a .module file
--features-bundle | Define module as feature using the given Features bundle name
--composer | Add a composer.json file
--dependencies | Module dependencies separated by commas (i.e. context, panels)
