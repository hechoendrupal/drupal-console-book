# ایجاد دستورات سفارشی

ساده‌ترین روش برای ایجاد یک کلاس سفارشی Command اجرای `generate:command` است.

اجرای دستور با استفاده از پرسش‌های تعاملی آن:
```
 // Welcome to the Drupal Command generator
 Enter the extension name [config_update]:
 > example

 Enter the Command name. [example:default]:
 >

 Enter the Command Class. (Must end with the word 'Command'). [DefaultCommand]:
 >

 Is the command aware of the drupal site installation when executed?. (yes/no) [no]:
 >

 Do you want to load services from the container (yes/no) [no]:
 > yes

Type the service name or use keyup or keydown.
This is optional, press enter to continue

 Enter your service [ ]:
 > entity_type.manager
 Enter your service [ ]:
 >

 Do you confirm generation? (yes/no) [yes]:
 >

Generated or updated files

 1 - modules/custom/example/src/Command/DefaultCommand.php
 2 - modules/custom/example/console.services.yml
 3 - modules/custom/example/console/translations/en/example.default.yml
```

اجرای `generate:command` و ارسال گزینه‌های خط فرمان، اطمینان یابید که دستور زیر مبتنی بر نیازمندی شما تنظیم شود.
```
drupal generate:command \
--extension="example" \
--extension-type="module" \
--class="DefaultCommand" \
--name="example:default" \
--services='entity_type.manager' \
--no-interaction
```

اجرای این دستور منجر به تولید یک کلاس Command جدید می‌گردد همراه با سرویس معرفی شده که کد اولیه برای ثبت آن آماده شده است.
