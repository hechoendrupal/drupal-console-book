# دریافت پروژه

کنسول دروپال یک پروژه ماژولار بوده که از چندین مخزن تشکیل می‌شود.

مخازن اصلی:
* [drupal/console](https://github.com/hechoendrupal/drupal-console)
* [drupal/console-core](https://github.com/hechoendrupal/drupal-console-core)
* [drupal/console-extend-plugin](https://github.com/hechoendrupal/drupal-console-extend-plugin)
* [drupal-console-dotenv](https://github.com/weknowinc/drupal-console-dotenv)

پروژه‌های اضافی:
* [drupal/console-develop](https://github.com/weknowinc/drupal-console-develop)
* [drupal-console-yaml](https://github.com/weknowinc/drupal-console-yaml)
        
زبان‌ها نیز درون مخازن جداگانه قرار می‌گیرند:
* [drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
* [drupal-console-fa](https://github.com/hechoendrupal/drupal-console-fa)

## Fork
مخازنی که قصد مشارکت در آن‌ها را دارید باید fork کنید. اینکار از رایط گرافیکی گیت‌هاب قابل انجام است.

## Clone
برای رونوشت‌گیری از مخزن fork شده باید یک دایرکتوری روی سیستم خود در نظر بگیرید. برای نمونه، `/Users/username/drupal-console-code`
```
cd /Users/username/drupal-console-code
git clone git@github.com:[your-github-user-here]/drupal-console.git
git clone git@github.com:[your-github-user-here]/drupal-console-core.git
git clone git@github.com:[your-github-user-here]/drupal-console-en.git
```

## نصب وابستگی‌ها
اکنون که مخازن مورد نظر خود را رونوشت‌گیری کرده‌اید، باید با استفاده از Composer وابستگی‌های مربوط به آن‌ها را دانلود کنید.
```
cd /Users/username/drupal-console-code/[cloned-repository]
composer install
```

به منظور آگاهی از چگونگی پیوند و آزمون این مخازن در یک سایت دروپالی قسمت بعد را مطالعه کنید.
