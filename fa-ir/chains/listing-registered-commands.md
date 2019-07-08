# فهرست دستورات ثبت شده

شما می‌توانید دستورات زنجیره‌ای شناسایی شده را با دستور `debug:chain` اشکال‌زدایی کنید.
```
 Directory /path/to/drupal8.dev/vendor/drupal/console-core/config/chain/
 ------------------------ --------------------
  File name.               Command name.
 ------------------------ --------------------
  develop-contribute.yml   develop:contribute
  quick-start.yml          quick:start
  site-new.yml             site:new
 ------------------------ --------------------
  
  Directory /path/to/drupal8.dev/console/chain/
 -------------------------- ----------------------
  File name.                 Command name.
 -------------------------- ----------------------
  build.yml                  build
  cache-rebuild-custom.yml   cache:rebuild:custom
  custom-test.yml
 -------------------------- ----------------------
```

برای هر عبارت زنجیره‌ای شناسایی شده که هنوز به عنوان دستور ثبت نشده ممکن است پیام زیر را مشاهده کنید.
```
/path/to/drupal8.dev/console/chain/custom-test.yml
 * You should register your chain file as command by providing metadata, more info at:
   https://docs.drupalconsole.com/en/chains/registering.html
```
