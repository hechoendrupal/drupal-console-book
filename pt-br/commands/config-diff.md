# config:diff
Mostra os itens de configuração que são diferentes na configuração ativa em comparação com um diretório.

**Utilização:**
```
drupal config:diff [arguments] [options]
cdi
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--reverse | Veja as mudanças em sentido inverso (por exemplo, diff de um diretório para a configuração ativa).

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
directory | O diretório para diferenciar. Se omitido, escolha dos diretórios de configuração do Drupal.

## Exemplos
* Forneça um diretório de configuração
```
drupal config:diff ../config/path
```
