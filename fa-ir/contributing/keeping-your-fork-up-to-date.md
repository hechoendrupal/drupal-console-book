# بروزنگهداری fork از پروژه

پس از گذشت زمان، مخزن fork شده شما و مخزن اصلی (که upstream نامیده می‌شود) از حالت همگام‌سازی خارج شده و شما با یک نسخه قدیمی از نرم‌افزار مواجه می‌شوید.

برای همگام‌سازی تغییرات خود با مخزن اصلی به صورت زیر عمل کنید:

## پیکربندی یک fork راه‌دور
یک مخزن upstream جدید را که به مخزن اصلی در گیت اشاره می‌کند، مشخص و پیکربندی کنید.
```
git remote add upstream https://github.com/hechoendrupal/drupal-console.git
```
برای اطلاعات بیشتر لطفا راهنمای [پیکربندی یک fork راه‌دور](https://help.github.com/articles/configuring-a-remote-for-a-fork/) در گیت‌هاب را مطالعه کنید.

## همگام‌سازی fork خود
fork خود را با مخزن upstream تعیین شده همگام سازید.
```
git fetch upstream
git merge upstream/master
```

برای اطلاعات بیشتر لطفا راهنمای [همگام‌سازی یک fork](https://help.github.com/articles/syncing-a-fork/) در گیت‌هاب را مطالعه کنید.
