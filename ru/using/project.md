# Использование проекта

Два типа команд Drupal Console

1. **Доступные глобально:** Команды, которые можено запустить из любой папки.
2. **Доступные отдельному сайту:** Команды, которые можено запустить только из папки с Drupal.

### Запуск Drupal Console из любой папки 

Drupal Console можно запустить из любой папки используя опцию `--root` option to define the Drupal root to be use in the command execution. 

```
drupal --root=/var/www/drupal8.dev cr all
```
**ВНИМАНИЕ:** При запуске Drupal Console из папки без Drupal без опции `--root` можно увидеть следующие сообщения:

Сообщение при запуске Drupal Console из папки без Drupal
> Перейдите в папку с Drupal, чтобы увидеть список всех комманд
> In order to list all of the available commands, you should run this inside a drupal root directory.

Сообщение при запуске Drupal Console из папки с неустановленным Drupal
> Установите Drupal, чтобы увидеть список всех комманд
> In order to list all of the available commands you should install drupal first.

Помните, что вам все еще нужно уствновить Drupal Console при сайте следуя иструкции [2.1](../getting/composer.md) при установленном сайте Drupal 8 и глобальном пусковом файле Drupal Console по иструкции [2.2](../getting/launcher.md).
