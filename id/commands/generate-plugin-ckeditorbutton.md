# generate:plugin:ckeditorbutton
Hasilkan tombol plugin CKEditor.

**application.gitbook.messages.usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | Nama modul.
--class | Nama kelas plugin
--label | Label plugin
--plugin-id | ID plugin. Catatan: Ini berhubungan pada nama plugin CKEditor. Ini merupakan argumen pertama pada fungsi CKEDITOR.plugins.add() pada berkas plugin.js.
--button-name | Nama tombol. Catatan: Ini berhubungan pada nama tombol CKEditor. Ini merupakan argumen pertama pada fungsi editor.ui.addButton() atau editor.ui.addRichCombo() pada berkas plugin.js.
--button-icon-path | Path dari gambar tombol. Ini merupakan path ke icon/gambar dari tombol.
