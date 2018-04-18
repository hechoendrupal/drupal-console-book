# config:export:content:type
Exportar um tipo de conteúdo específico e os seus campos.

**Utilização:**
```
drupal config:export:content:type [arguments] [options]
cect
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--optional-config | Exportar tipo de conteúdo como um arquivo de configuração YAML opcional em seu módulo.
--remove-uuid | If set, the configuration will be exported without uuid key.
--remove-config-hash | If set, the configuration will be exported without the default site hash key.

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
content-type | Content Type to be exported

## Exemplos
* Provide a content type  and module name
```
drupal config:export:content:type page \
  --module="demo"
```
* If you want export content type provide the optional config
```
drupal config:export:content:type page \
  --module="demo" \
  --optional-config
```
