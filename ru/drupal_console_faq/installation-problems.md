# Проблемы во время установки 


Когда вы запускаете DrupalConsole из Drupal 8 каталога, вы можете увидеть различные сообщения об ошибках. Мы попробуем собрать все ошибки, о которых нам сообщили, и показать как их можно исправить.

--- 

### Сообщение об ошибке:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
Вам надо отредактировать значение 'host' в вашем файле 'settings.php'.

Откройте `sites/default/settings.php`. В вашем файле `settings.php`, поменяйте значение `host`:
```
'host' => '127.0.0.1'
```
или если ваш файл 'settings.php' уже имеет это значение:
```
'host' => '127.0.0.1'
```
поменяйте его на:
```
'host' => 'localhost'. 
```
После того, как вы добавили ваши изменения, обязательно сохраните файл и затем запустите DrupalConsole заново.

---

### Сообщение об ошибке:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
Создайте символическую ссылку указывающую на `/tmp/mysql.sock`:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```

---

### Сообщение об ошибке:
```
Fatal error: require(): Failed opening required 'drupal.php'
```
Причиной этой ошибки может быть загрузчик ioncube расширения, который используется для кодирования и декодирования PHP файлов. Это расширение блокирует нормальную работу phar файлов с вызовами require/include. Вам необходимо деактивировать это расширение.
