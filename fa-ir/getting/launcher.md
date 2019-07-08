# نصب راه‌انداز کنسول دروپال با استفاده از Phar

```
curl https://drupalconsole.com/installer -L -o drupal.phar
mv drupal.phar /usr/local/bin/drupal
chmod +x /usr/local/bin/drupal
```
یادداشت: اگر ابزار curl را ندارید می‌توانید به صورت مستقیم از php استفاده کنید
```
php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar
```

## بروزرسانی راه‌انداز DrupalConsole
```
drupal self-update
```

## اجرای کنسول دروپال با استفاده از راه‌انداز
```
drupal
```

بایستی فایل راه‌انداز را از درون یک سایت دروپالی اجرا کنید یا اینکه از گزینه `--root=/path/to/drupal8.dev` برای مشخص کردن مسیر دروپال بهره بگیرید.

**یادداشت:** `drupal` فقط یک نام مستعار است و شما می‌توانید آن را به هر چه می‌خواهید تغییر دهید.
