# generate:plugin:imageeffect
Criar plugin de efeito de imagem.

**Utilização:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--class | Nome da classe do plugin
--label | Label do plugin
--plugin-id | Id do plugin
--description | Descrição do plugin

## Exemplos
* Generate a image effect plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
