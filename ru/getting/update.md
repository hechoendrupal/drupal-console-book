# Обновления проекта
Drupal 8 находится в постоянной разработке, соответсвенно и Drupal Console. Самый легкий способ обновления Drupal Console - это использование команды `self-update`.

## В зависимости от метода установки:

### Drupal Console установлен глобально (и переименован в "drupal"):
```
$ drupal self-update
```

### Drupal Console установлен глобально (c помощью Composer):
```
$ composer global update drupal/console:@stable
```

### Drupal Console установлен локально (файл console.phar в дериктории проекта):
```
$ php console.phar self-update
```

