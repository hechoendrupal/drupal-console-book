# yaml:diff
The **yaml:diff** command Сравнение двух YAML файлов и определение различий между ними

**Usage:**
```
$ drupal yaml:diff [arguments] [options] 
$ yd  
```

## Available options
Option | Details
-------|-------------
--stats | Print statistics about YAML files comparation
--negate | Определить режим разности или сравнения, возможные значения TRUE/FALSE или 0/1
--limit | Ограничить результат до числа
--offset | Смещение стартовой позиции

## Available arguments
Argument | Details
---------|-------------
yaml-left | Базовый YAML файл для сравнения
yaml-right | YAML файл сравниваемый с базовым, для выявления различий
