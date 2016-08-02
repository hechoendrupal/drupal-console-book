# config:override
Override config value in active configuration.

**使い方:**
```
$ drupal config:override [arguments]
$ co  
```

## 利用可能な引数
引数 | 詳細
---------|-------------
name | Configuration name
key | Key
value | Value

## 例
* Définir la valeur de "flood" du module Contact à 10.
```
$ drupal config:override contact.settings flood.limit 10
```
