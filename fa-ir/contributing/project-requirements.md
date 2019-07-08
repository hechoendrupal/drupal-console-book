# پیشنیازهای پروژه

## دانلود گیت
توصیه می‌کنیم که گیت را از مسیر [http://git-scm.com/downloads](http://git-scm.com/downloads) دانلود کنید.

## دانلود کامپوزر

دستور زیر را در ترمینال اجرا کرده تا آخرین نسخه از Composer را دریافت کنید:
```
curl -sS https://getcomposer.org/installer | php
```
و در صورتی که curl ندارید:
```
php -r "readfile('https://getcomposer.org/installer');" | php
```
این اسکریپت نصب، تنها برخی تنظیمات php.ini را بررسی کرده و در صورت اشتباه بودن آن‌ها به شما هشدار می‌دهد، سپس آخرین نسخه از composer.phar را درون دایرکتوری فعلی دانلود می‌کند.

به منظور دسترسی سراسری به composer دستور زیر را اجرا کنید:
```
mv composer.phar /usr/local/bin/composer
```
