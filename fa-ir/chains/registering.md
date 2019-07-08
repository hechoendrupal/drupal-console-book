# ثبت به عنوان دستورات معمولی

تعریف عبارت‌های زنجیره‌ای می‌تواند شامل اطلاعات تکمیلی باشد که آن‌ها را به عنوان در دستور معمولی دیگر در کنسول دروپال قابل اجرا کند.

برای ثبت به عنوان یک دستور معمولی باید قسمت `command` شامل `name` و `description` را بیفزایید.

```
command:
  name: build
  description: 'Build site'
vars:
  profile:
    - standard
    - minimal
commands:
  # Install site
  - command: site:install
    options:
      force: true
    arguments:
      profile: "{{ profile }}"
  # Import configuration
  - command: config:import
    options:
      skip-uuid: true
  # Rebuild caches.
  - command: cache:rebuild
    arguments:
        cache: all

```

پس از افزودن قسمت مورد نظر باید بتوانید دستور `build` را هنگام اجرای دستور `list` مشاهده کنید.
