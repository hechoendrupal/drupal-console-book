# مشکلات نصب

زمانی که DrupalConsole را از دایرکتوری دروپال ۸ خود اجرا می‌کنید، ممکن است پیام‌های خطای گوناگونی دریافت کنید. در این قسمت سعی می‌کنیم که متداول‌ترین این پیام‌ها همراه با جواب را به شما نشان دهیم.

--- 

### پیام خطا:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
شما باید گزینه 'host' در فایل 'settings.php' را ویرایش کنید.

به مسیر `sites/default/settings.php` بروید. در فایل `settings.php` خود، مقدار `host` را به شکل زیر تغییر دهید:
```
'host' => '127.0.0.1'
```
یا اگر فایل 'settings.php' دارای مقدار زیر است:
```
'host' => '127.0.0.1'
```
آن را به مقدار زیر تغییر دهید:
```
'host' => 'localhost'. 
```
پس از اینکه تغییر ایجاد شد، اطمینان یابید که فایل ذخیره‌سازی شده است و دوباره DrupalConsole را اجرا نمایید.

---

### پیام خطا:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
ایجاد یک پیوند نمادین که به `/tmp/mysql.sock` اشاره می‌کند:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```

---

### پیام خطا:
```
Fatal error: require(): Failed opening required 'drupal.php'
```
این خطا می‌تواند توسط افزونه ioncube ایجاد شود، که برای کدگذاری و کدگشایی فایل‌های PHP استفاده می‌شود. این افزونه عملکرد عادی تمام فایل‌های phar که شامل فراخوانی‌های require/include باشند را مختل می‌کند. شما باید این افزونه را غیرفعال کنید.

---

### پیام اخطار:
```
The configuration date.timezone was missing and overwritten with America/Tijuana.
```
منطقه زمانی شما در فایل php.ini تنظیم نشده است؛ شما باید این مشکل را با ویرایش فایل موجود برطرف کنید (یک فایل php.ini جداگانه برای CLI نیز وجود دارد).

دستور `php --ini` را اجرا کرده و به دنبال "Loaded Configuration File" بگردید. برای نمونه، در اوبونتو:
```
Loaded Configuration File:         /etc/php5/cli/php.ini
```
این فایل را ویرایش کرده و به دنبال عبارت زیر بگردید:
```
;date.timezone =
```
این خط را از حالت غیرفعال خارج کرده و منطقه زمانی مناسب خود را از http://php.net/manual/en/timezones.php پیدا کنید.
