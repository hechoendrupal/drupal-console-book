# config:export:view
Exportar uma view no formato YAML em um módulo, para reutilizar em outro website.

**Uso:**
```
$ drupal config:export:view [arguments] [options]
$ cev  
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--module | O nome do módulo.
--optional-config | Exportar a view como uma configuração YAML opcional em seu módulo
--include-module-dependencies | Incluir as dependências do módulo em um arquivo YAML de informação do módulo

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
view-id | ID da view
