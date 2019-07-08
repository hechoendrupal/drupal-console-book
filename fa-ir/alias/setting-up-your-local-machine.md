# راه‌اندازی ماشین محلی خود

استفاده از نام مستعار یک سایت نیازمند برخی پیکربندی‌های است.

## پیکربندی سراسری

پیکربندی‌های سراسری می‌توانند با استفاده از فایل `~/.console/config.yml` فراهم شوند. این اطلاعات به صورت گروه‌بندی شده درون کلید `remote` قرار می‌گیرند.

```
application:
  ...
  remote:
    user: drupal
    port: 22
    options:
    arguments:
    type: ssh
```

## پیکربندی محلی

پیکربندی نام مستعار سایت می‌تواند با استفاده از یک فایل YAML درون `/path/to/site/console/sites/sample.yml` یا `~/.console/sites/sample.yml` فراهم شود.

```
local:
  root: /var/www/drupal8.dev
  type: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
  type: ssh
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  type: ssh
```

## فهرست نام‌های مستعار

تمام سایت‌های شناخته شده می‌توانند توسط دستور `debug:site` فهرست شوند.

```
drupal debug:site

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

جزئیات پیکربندی یک سایت می‌تواند با ارسال نام سایت به عنوان آرگومان برای دستور `debug:site` نمایش داده شود.
```
drupal debug:site sample.dev

user: drupal
port: 22
options:
arguments:
root: /var/www/html/drupal
host: 140.211.10.62
type: ssh
```

**یادداشت:** شاید تشخیص داده باشید که پیکربندی‌های سراسری و محلی هنگام دیباگ یک سایت با یکدیگر ادغام می‌شوند. پس می‌توانید هر یک از پیکربندی‌های سراسری را با قرار دادن کلیدشان در پیکربندی محلی بازنویسی کنید.
