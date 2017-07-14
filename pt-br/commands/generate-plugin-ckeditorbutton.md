# generate:plugin:ckeditorbutton
Gerar um Plugin de botão CKEditor.

**application.gitbook.messages.usage:**
```
drupal generate:plugin:ckeditorbutton [options]
gpc
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--module | O nome do módulo.
--class | Nome da classe do Plugin
--label | Plugin label
--plugin-id | Plugin ID. Observação: Corresponde ao name do Plugin CKEditor. É o primeiro argumento da função CKEDITOR.plugins.add() no arquivo plugin.js.
--button-name | Nome do botão. Observação: Corresponde ao nome do botão do Plugin CKEditor. É o primeiro argumento da função editor.ui.addButton() ou editor.ui.addRichCombo() no arquivo plugin.js.
--button-icon-path | Path do Ícone do Botão. É o caminho do ícone/imagem do botão.
