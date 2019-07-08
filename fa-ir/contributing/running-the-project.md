# اجرای پروژه
به منظور مشارکت، شما به سایت دروپالی نیاز دارید که به بسته‌های clone و fork شده موجود متصل باشد.

## اجرای فرآیند خودکارسازی
DrupalConsole شامل دستوری است که تمام این فرآیند را برای شما انجام می‌دهد.
```
drupal develop:contribute \
--drupal=/path/to/drupal8.dev \
--code=/Users/username/drupal-console-code/
```

گزینه `--drupal` دایرکتوری است که سایت جدید دروپالی در آن ایجاد و گزینه `--code` دایرکتوری است که مخازن گوناگون از DrupalConsole در آن قرار گرفته‌اند.

> یادداشت:
>
> به منظور رونوشت‌گیری از فایل `~/.console/chain/develop-contribute.yml` در سیستم محلی خود، ابتدا باید دستور `drupal init` را اجرا کنید.
>
اطمینان یابید که آخرین نسخه از DrupalConsole نصب شده باشد. برای اینکار می‌توانید مطابق با دستورات [این قسمت](https://github.com/hechoendrupal/drupal-console-launcher/blob/master/README.md) عمل کنید.

## اجرای تمام گام‌ها به صورت دستی
اگر می‌خواهید که تمام گام‌ها را به صورت دستی اجرا کنید باید طبق دستورات زیر عمل کنید:

### دانلود دروپال و کنسول دروپال
```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

### نصب دروپال با استفاده از  SQLite
```
drupal site:install standard --db-type="sqlite" --no-interaction
```
> یادداشت: شما می‌توانید دروپال را با استفاده از MySQL و با استفاده از دستور `site:install` یا ارسال گزینه‌های مورد نیاز نصب کنید.

### دانلود بسته توسعه کنسول دروپال
```
composer require drupal/console-develop --dev
```

### ایجاد یک پیوند نمادین بین دروپال و مخازنی که fork شده‌اند
```
drupal develop:create:symlinks \
--code-directory=/Users/username/drupal-console-code/
```

## دانلود زبان یا بسته‌های اضافی کنسول دروپال

اگر می‌خواهید که در ترجمه کنسول دروپال به [فارسی](https://github.com/hechoendrupal/drupal-console-fa) مشارکت کنید باید:

۱.- آن را روی سایت دروپالی با اجرای دستور زیر دانلود کنید.

```
composer require drupal/console-fa
```

۲.- مخزن مورد نظر را درون سیستم محلی خود fork و clone کنید.

۳.- دستور `develop:create:symlinks` را به منظور ایجاد پیوندهای نمادین بین دروپال و بسته‌های تازه اضافه شده اجرا کنید.

اینکار در مورد زبان‌ها و بسته‌های اضافی صدق می‌کند. برای نمونه، [drupal/console-yaml](https://github.com/weknowinc/drupal-console-yaml).

## جمع‌بندی

اکنون می‌توانید تغییرات مورد نظر خود را اعمال کرده و در پروژه مشارکت کنید. در انتها نیز یک PR به مخزن اصلی پروژه ارسال کنید.

کدنویسی خوش بگذره!‌ ممنون که در کنسول دروپال مشارکت می‌کنی.
