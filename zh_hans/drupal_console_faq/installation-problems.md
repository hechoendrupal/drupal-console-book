# 安装问题 

When you run DrupalConsole from your Drupal 8 root directory, you can get different error messages, we will try to compile the reported issues and how to have them fixed.

--- 

错误消息:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
你需要编辑 `settings.php` 文件中的 `host` 

定位到 `sites/default/settings.php` 这个文件， 在 `settings.php` 文件中, 改变 `host` ：
```
'host' => '127.0.0.1'
```
或者如果 'settings.php' 文件中已经是这样：
```
'host' => '127.0.0.1'
```
改为：
```
'host' => 'localhost'. 
```
改为以后，确认保存了文件，然后再次运行 Drupal Console。

---

错误信息:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
创建一个符号链接到 `/tmp/mysql.sock`:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```

---

错误信息:
```
Fatal error: require(): Failed opening required 'drupal.php'
```
ioncube loader 扩展可以导致这个错误，这个扩展被用于编解码 PHP 文件，它会阻止任何包含 require/include 调用的 phar 文件。你必须禁用这个扩展。