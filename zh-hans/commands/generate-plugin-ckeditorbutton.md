# generate:plugin:ckeditorbutton
生成 CKEditor 按钮插件

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal generate:plugin:ckeditorbutton [options]
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--module | 模块名称
--class | 插件类名
--label | 插件标签
--plugin-id | 插件 ID. 注意: 这与 CKEditor 插件名称对应. 它是 plugin.js 文件中 CKEDITOR.plugins.add() 函数的第一个参数
--button-name | 按钮名称. 注意: 这与 CKEditor 按钮名称相对应. 它是 plugin.js 文件中 editor.ui.addButton() 或 editor.ui.addRichCombo() 函数的第一个参数
--button-icon-path | 按钮图标路径. 这个路径是按钮图标或图像的路径
