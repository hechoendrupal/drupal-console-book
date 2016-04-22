# generate:plugin:ckeditorbutton
Generate CKEditor button plugin.

**प्रयोग:**
```
$ drupal generate:plugin:ckeditorbutton [options]
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--module | मोड्यूल का नाम।
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin ID. NOTE: This corresponds to the CKEditor plugin name. It is the first argument of the CKEDITOR.plugins.add() function in the plugin.js file.
--button-name | Button name. NOTE: This corresponds to the CKEditor button name. They are the first argument of the editor.ui.addButton() or editor.ui.addRichCombo() functions in the plugin.js file.
