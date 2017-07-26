# Установка пускового файла Drupal Console

С помощью командного приложения curl:

```
curl https://drupalconsole.com/installer -L -o drupal.phar
mv drupal.phar /usr/local/bin/drupal
chmod +x /usr/local/bin/drupal
```

ИЛИ если командное приложение curl не установлено

```
php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## Обновление пускового файла Drupal Console

```
drupal self-update
```

## Запуск пускового файла Drupal Console

```
$ drupal
```

Пусковой файл Drupal Console можно запустить из папки, где установлен Drupal
или указав флаг `--root=/путь/к/drupal8.dev`.

**ВНИМАНИЕ:** Имя файла `drupal` - всего лишь псевдоним (алиас) и файлу 
можно присвоить любое имя.
