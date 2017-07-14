# generate:plugin:ckeditorbutton
CKEditor बटन प्लगइन उत्पन्न करें।

**Usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगइन क्लास नाम
--label | प्लगइन लेबल
--plugin-id | प्लगइन आईडी। नोट: यह CKEditor प्लगइन नाम से मेल खाती है। यह plugin.js फ़ाइल में CKEDITOR.plugins.add() फंक्शन के पहले आर्गुमेंट है।
--button-name | बटन नाम। नोट: यह CKEditor बटन नाम से मेल खाती है। वे plugin.js फ़ाइल में editor.ui.addButton() या editor.ui.addRichCombo() फ़ंक्शंस का पहला आर्गुमेंट हैं।
--button-icon-path | बटन आइकन पथ। इस बटन के आइकन/इमेज के लिए मार्ग है।

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
