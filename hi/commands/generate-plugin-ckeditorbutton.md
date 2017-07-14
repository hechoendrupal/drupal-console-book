# generate:plugin:ckeditorbutton
CKEditor बटन प्लगइन उत्पन्न करें।

**application.gitbook.messages.usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगइन क्लास नाम
--label | प्लगइन लेबल
--plugin-id | प्लगइन आईडी। नोट: यह CKEditor प्लगइन नाम से मेल खाती है। यह plugin.js फ़ाइल में CKEDITOR.plugins.add() फंक्शन के पहले आर्गुमेंट है।
--button-name | बटन नाम। नोट: यह CKEditor बटन नाम से मेल खाती है। वे plugin.js फ़ाइल में editor.ui.addButton() या editor.ui.addRichCombo() फ़ंक्शंस का पहला आर्गुमेंट हैं।
--button-icon-path | बटन आइकन पथ। इस बटन के आइकन/इमेज के लिए मार्ग है।
