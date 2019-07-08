# نصب کنسول دروپال با استفاده از Composer

دایرکتوری را به سایت دروپال تغییر دهید:
```
cd /path/to/drupal8.dev
```

دستور composer require را اجرا کنید:
```
composer require drupal/console:~1.0 \
--prefer-dist \
--optimize-autoloader
```

## دانلود با استفاده از قالب پروژه DrupalComposer
```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

## بروزرسانی DrupalConsole
```
composer update drupal/console --with-dependencies
```
