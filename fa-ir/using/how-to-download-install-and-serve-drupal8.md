# چگونگی دانلود، نصب و راه‌اندازی دروپال ۸

ساده‌ترین روش برای امتحان کردن دروپال ۸ در ماشین خود، اجرای دستور `quick:start` است.

```
drupal quick:start
```
> یادداشت: به منظور رونوشت‌گیری از فایل `~/.console/chain/quick-start.yml` در سیستم خود، ابتدا باید `drupal init` را اجرا کنید.

دستور `chain` به شما کمک می‌کند تا اجرای دستورات را به صورت خودکار انجام دهید، به صورتی که ابتدا یک فایل خارجی YAML را تعریف می‌کنید و مجموعه دستورات، گزینه‌ها و آرگومان‌های مورد نیاز را پشت سر هم قرار می‌دهید تا به ترتیبی که قرار دارند اجرا شوند.

محتوای فایل `~/.console/chain/quick-start.yml` عبارت است از:
```
# How to use
# quick:start --directory="/path/to/drupal-project/"
# quick:start --directory="/path/to/drupal-project/" --profile="minimal"
# quick:start --repository="acquia/lightning-project:^8.1" --directory="/path/to/drupal-project/" --profile="lightning"
command:
  name: quick:start
  description: 'Download, install and serve a new Drupal project'
vars:
  repository:
    - drupal-composer/drupal-project:8.x-dev
    - acquia/lightning-project
    - acquia/reservoir-project
  profile: standard
commands:
  # Create Drupal project using DrupalComposer
  - command: exec
    arguments:
      bin: composer create-project %{{repository}} %{{directory}} --prefer-dist --no-progress --no-interaction
  # Install Drupal
  - command: exec
    arguments:
      bin: drupal site:install %{{profile}} --root=%{{directory}} --db-type="sqlite" --no-interaction
  # Start PHP built-in server
  - command: exec
    arguments:
      bin: drupal server --root=%{{directory}}ß
```

پیکربندی فوق به اجرای چندین دستور می‌پردازد، در این مورد دستوراتی که دروپال را دانلود کرده و در قالب SQLite نصب می‌کند و در نهایت با راه‌اندازی سرور درونی PHP به شما امکان مرور سایت را از نشانی 127.0.0.1:8088 می‌دهد.

شما می‌توانید محتوای این فایل را برداشته و تغییراتی روی آن انجام دهید، برای نمونه دستوراتی برای دانلود افزونه `module:download`، نصب افزونه `module:install`، واردسازی پیکربندی `config:import`، بازیابی پایگاه‌داده `database:restore` یا هر دستور دیگری که توسط DrupalConsole یا افزونه‌های سفارشی پشتیبانی می‌شود.
