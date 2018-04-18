# generate:plugin:block
Criar plugin de bloco.

**Utilização:**
```
drupal generate:plugin:block [options]
gpb
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Nome da classe do plugin
--label | Label do plugin
--plugin-id | Id do plugin
--theme-region | Região do tema para renderizar o Bloco
--inputs | Cria entradas de formulário.
--services | Carrega serviços do container.

## Exemplos
* Generate a plugin block in the header region with an input field specifying the module name, the class, the label, its id, the region and the input
```
drupal generate:plugin:block  \
  --module="modulename"  \
  --class="DefaultBlock"  \
  --label="Default block"  \
  --plugin-id="default_block"  \
  --theme-region="header"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
