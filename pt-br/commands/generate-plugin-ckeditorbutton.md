# generate:plugin:ckeditorbutton
Gerar um Plugin de botão CKEditor.

**Utilização:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Nome da classe do Plugin
--label | Plugin label
--plugin-id | Plugin ID. Observação: Corresponde ao name do Plugin CKEditor. É o primeiro argumento da função CKEDITOR.plugins.add() no arquivo plugin.js.
--button-name | Nome do botão. Observação: Corresponde ao nome do botão do Plugin CKEditor. É o primeiro argumento da função editor.ui.addButton() ou editor.ui.addRichCombo() no arquivo plugin.js.
--button-icon-path | Path do Ícone do Botão. É o caminho do ícone/imagem do botão.

## Exemplos
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
