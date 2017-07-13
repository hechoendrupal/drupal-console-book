# yaml:diff
Comparar dois arquivos YAML para determinar diferenças entre eles

**Uso:**
```
$ drupal yaml:diff [arguments] [options]
$ yd  
```

## Opções disponíveis
Opção | Detalhes
-------|-------------
--stats | Exibir estatísticas sobre a comparação dos arquivos YAML
--negate | Definir modo de comparação, possíveis valores são TRUE/FALSE ou 0/1
--limit | Limitar resultados a uma quantidade pré específicadaLimit results to a specific number
--offset | Ponto de início dos resultados

## Argumentos disponíveis
Argumento | Detalhes
---------|-------------
yaml-left | Arquivo YAML base
yaml-right | Arquivo YAML a ser comparado
