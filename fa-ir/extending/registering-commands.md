# ثبت دستورات

برای فعال‌سازی دستورات کنسول در یک محیط دروپال، نیاز دارید که کلاس دستور خود را به عنوان یک سرویس درون فایل `console.services.yml` واقع در دایرکتوری اصلی (افزونه، قالب یا پروفایل) قرار داده و تعریف سرویس را به صورت `drupal.command` برچسب‌گذاری کنید.
```
services:
  example.example_default:
    class: Drupal\example\Command\DefaultCommand`
    arguments: ['@entity_type.manager']
    tags:
      - { name: drupal.command }
```
> یادداشت: قسمت `arguments` در تعریف سرویس اختیاری بوده و تنها در صورت استفاده از سرویس از درون container مورد نیاز خواهد بود.
