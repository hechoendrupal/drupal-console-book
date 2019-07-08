# اتصال به یک محیط مجازی

با فراهم کردن مقادیر مناسب برای گزینه‌های `extra-options` و `type` می‌توانید به یک ماشین مجازی متصل شوید.

## مثالی از DrupalVM
```
dev:
  root: /var/www/drupalvm/drupal
  host: 192.168.88.88
  user: vagrant
  extra-options: '-o PasswordAuthentication=no -i ~/.vagrant.d/insecure_private_key'
  type: ssh
```

##  مثالی از Drupal4Docker
```
dev:
  root: /var/www/html
  extra-options: docker-compose exec --user=82 php
  type: container
```
هنگام اتصال با استفاده از `type: container` نیازی به فراهم کردن مقادیر `host` و `user` نیست.
