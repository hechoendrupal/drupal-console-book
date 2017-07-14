# generate:plugin:ckeditorbutton
CKEditor बटण प्लगइन उत्पन्न करा.

**Usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव
--label | प्लगइन लेबल
--plugin-id | प्लगिन आयडी. टीप: हा CKEditor प्लगइन नावाशी संबंधित आहे. Plugin.js फाइलमध्ये CKEDITOR.plugins.add() फंक्शनलचा पहिला तर्क आहे.
--button-name | बटण नाव सुचना: हे CKEditor बटनचे नाव आहे. ते plugin.ui.addButton() किंवा editor.ui.addRichCombo() फंक्शन्स प्लगइन.जेएस फाईलमधील पहिले तर्क आहेत.
--button-icon-path | बटण चिन्ह पथ हे बटण च्या चिन्ह / प्रतिमा पथ आहे.

## Examples
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
