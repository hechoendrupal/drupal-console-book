# دستور زنجیره‌ای چیست

یک دستور `chain` دستوری سفارشی است که به شما در خودکارسازی اجرای چندین دستور یاری می‌رساند. با تعریف و خواندن فایل YAML خارجی که شامل نام، گزینه‌ها و آرگومان‌های چندین دستور است به شما امکان اجرای آن‌ها مطابق با ترتیب موجود در فایل را می‌دهد.

## ویژگی‌های دستور زنجیره‌ای:

### شناسایی فایل‌های YAML
دستورات زنجیره‌ای از مسیرهای زیر شناسایی می‌شوند:
* **سراسری** `~/.console/chain` 
* **برای هر سایت** `path/to/site/console/chain`

### تعریف عبارت‌های جانشین
شما می‌توانید عبارت‌های جانشین را با استفاده از `{{name}}` و --key=value را از رابط خط فرمان با گزینه `--name=[VALUE]` هنگام اجرای دستور فراخوانی کنید.

اگر عبارت جانشینی تعریف کنید و مقداری برای آن هنگام استفاده در رابط خط فرمان ارسال نکنید، اینکار در حالت اجرای تعاملی به یک پرسش تبدیل می‌شود.
```
commands:
  # Create Drupal project using DrupalComposer
  - command: exec
    arguments:
      bin: composer create-project {{repository}} {{directory}} --prefer-dist --no-progress --no-interaction
  # Install Drupal
  - command: exec
    arguments:
      bin: drupal site:install {{profile}} --root={{directory}} --db-type="sqlite" --no-interaction
  # Start PHP built-in server
  - command: exec
    arguments:
      bin: drupal server --root={{directory}}
```

### تنظیم مقادیر پیشفرض برای عبارت‌های جانشین
در قسمت `variables` می‌توانید مقادیر پیشفرض برای عبارت‌های جانشین را تعریف کنید.
```
vars:
  repository:
    - drupal-composer/drupal-project:8.x-dev
    - acquia/lightning-project
    - acquia/reservoir-project
  profile: standard
```

می‌توانید عبارت‌های جانشین را به عنوان مقدار تکی یا یک آرایه نیز تعریف کنید. از این تعریف هنگام تصمیم‌گیری درباره پرسش مطرح شده در حالت تعاملی اجرای دستور استفاده خواهد شد.

### خواندن متغیرهای محلی
با استفاده از `{{ env("ENVIRONMENT_VAR_NAME") }}` می‌توانید متغیرهای محلی را بخوانید.
```
command:
  name: site:install:env
  description: 'Install site using environment placeholders'
commands:
  # Install Drupal
  - command: site:install
    options:
      langcode: en
      db-type: '{{ env("DATABASE_TYPE") }}'
      db-host: '{{ env("DATABASE_HOST") }}'
      db-name: '{{ env("DATABASE_NAME") }}'
      db-user: '{{ env("DATABASE_USER") }}'
      db-pass: '{{ env("DATABASE_PASSWORD") }}'
      db-port: '{{ env("DATABASE_PORT") }}'
      site-name: 'Drupal 8 site'
      site-mail: admin@example.org # default email
      account-name: admin # default account
      account-mail: admin@example.org # default email
      account-pass: admin # default pass
    arguments:
      profile: 'standard'
```
تمام متغیرهای محلی مورد نیاز در تعریف دستور زنجیره‌ای اجباری هستند.
