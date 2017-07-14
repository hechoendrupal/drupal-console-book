# generate:plugin:ckeditorbutton
Hasilkan tombol plugin CKEditor.

**Usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Available options
Option | Details
-------|-------------
--module | Nama modul.
--class | Nama kelas plugin
--label | Label plugin
--plugin-id | ID plugin. Catatan: Ini berhubungan pada nama plugin CKEditor. Ini merupakan argumen pertama pada fungsi CKEDITOR.plugins.add() pada berkas plugin.js.
--button-name | Nama tombol. Catatan: Ini berhubungan pada nama tombol CKEditor. Ini merupakan argumen pertama pada fungsi editor.ui.addButton() atau editor.ui.addRichCombo() pada berkas plugin.js.
--button-icon-path | Path dari gambar tombol. Ini merupakan path ke icon/gambar dari tombol.

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
