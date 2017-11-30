# Создание новых команд

Самый простой способ создать новый Command класс это извлечь `generate:command` команду.

Выполнить команду, используя интерактивный метод извлечения команд: 
```
 $ drupal generate:command
 
 // Welcome to the Drupal Command generator
 Enter the module name [devel]:
 > example

 Enter the Command name. [example:default]:
 >

 Enter the Command Class. (Must end with the word 'Command'). [DefaultCommand]:
 >

 Is the command aware of the drupal site installation when executed?. (yes/no) [yes]:
 >

 Do you confirm generation? (yes/no) [yes]:
 >

Generated or updated files
 Site path: /var/www/drupal.dev
 1 - modules/custom/example/src/Command/DefaultCommand.php
```

Выполнить команду`generate:command`, передав встроенные опции. Убедитесь, что вы отредактировали следующую команду согласно вашим требованиям.

```
$ drupal generate:command  --module=example --class=DefaultCommand --name=example:default --container-aware -y
```
Исполнение этой команды сгенерирует новый Command класс содержащий шаблон необходимый для регистрации новой команды внутри вашего модуля Drupal.
