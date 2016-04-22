# generate:plugin:ckeditorbutton
Generate CKEditor button plugin.

**用法:**
```
$ drupal generate:plugin:ckeditorbutton [options]
```

## 可用选项
选项 | 详细
-------|-------------
--module | 模块名称
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin ID. NOTE: This corresponds to the CKEditor plugin name. It is the first argument of the CKEDITOR.plugins.add() function in the plugin.js file.
--button-name | Button name. NOTE: This corresponds to the CKEditor button name. They are the first argument of the editor.ui.addButton() or editor.ui.addRichCombo() functions in the plugin.js file.
