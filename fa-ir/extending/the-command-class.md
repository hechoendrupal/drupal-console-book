# کلاس Command

دستورات سفارشی باید از کلاس‌های فراهم شده توسط پروژه DrupalConsole تبعیت کنند.

## گسترش کلاس پایه `Command`

با گسترش کلاس پایه `Command`، دستور شما قادر خواهد بود تا از ویژگی‌های چند-زبانه فراهم شده توسط DrupalConsole بهره‌مند شود.

۱.- کلاس `Command` را وارد کنید.
```
use Drupal\Console\Core\Command\Command;
```

۲.- کلاس `Command` را گسترش دهید.
```
class DefaultCommand extends Command
```

## گسترش کلاس `ContainerAwareCommand`

با گسترش کلاس `ContainerAwareCommand` در دستور خود (بجای کلاس پایه `Command`)، به service container دسترسی پیدا خواهید کرد.

به عبارت دیگر، می‌توانید به هر کدام از سرویس‌های پیکربندی شده دروپال با استفاده از متد `get` دسترسی یابید.

۱.- کلاس `ContainerAwareCommand` را وارد کنید.
```
use Drupal\Console\Core\Command\ContainerAwareCommand;
```

۲.- کلاس `ContainerAwareCommand` را گسترش دهید.
```
class DefaultCommand extends ContainerAwareCommand
```
