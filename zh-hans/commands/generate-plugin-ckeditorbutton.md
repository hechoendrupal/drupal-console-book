# generate:plugin:ckeditorbutton
生成 CKEditor 按钮插件

**使用方法:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--class | 插件类名
--label | 插件标签
--plugin-id | 插件 ID. 注意: 这与 CKEditor 插件名称对应. 它是 plugin.js 文件中 CKEDITOR.plugins.add() 函数的第一个参数
--button-name | 按钮名称. 注意: 这与 CKEditor 按钮名称相对应. 它是 plugin.js 文件中 editor.ui.addButton() 或 editor.ui.addRichCombo() 函数的第一个参数
--button-icon-path | 按钮图标路径. 这个路径是按钮图标或图像的路径

## 例子
* Generate CKEditor button specifying the module name, the class, the label, its id, the button name and the icon path
```
drupal generate:plugin:ckeditorbutton  \
  --module="modulename"  \
  --class="DefaultCKEditorButton"  \
  --label="Default ckeditor button"  \
  --plugin-id="default ckeditor button"  \
  --button-name="Default ckeditor button"  \
  --button-icon-path="modules/custom/modulename/js/plugins/default ckeditor button/images/icon.png"
```
