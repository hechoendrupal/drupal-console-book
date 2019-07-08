# دریافت سرویس‌ها از Service Container

به شیوه‌های زیر می‌توانید از service container درخواست سرویس کنید:

### قراردادن سرویس‌ها درون کلاس Command

استفاده از قسمت `arguments` هنگام ثبت کلاس Command در فایل `console.services.yml`.
```
services:
  example.example_default:
    class: Drupal\example\Command\DefaultCommand`
    arguments: ['@entity_type.manager']
    tags:
      - { name: drupal.command }
```

افزودن یک متغیر محافظت شده.
```
  /**
   * The $entityTypeManager definition.
   *
   * @var EntityTypeManager
   */
  protected $entityTypeManager;
```

ارسال سرویس با استفاده از متد `__construct`
```
  /**
   * Constructs a new DefaultCommand object.
   */
  public function __construct(EntityTypeManager $entity_type_manager) {
    $this->entityTypeManager = $entity_type_manager;
    parent::__construct();
  }
```

### گسترش کلاس پایه `ContainerAwareCommand` در کلاس Command

با استفاده از این روش شما به service container دسترسی دارید، به عبارت دیگر، به هر سرویس پیکربندی شده موجود توسط متد `get` دسترسی دارید.

```
protected function execute(InputInterface $input, OutputInterface $output)
{
    $uid = $input->getArgument('uid');
    $entityTypeManager = $this->get('entity_type.manager');;
    if ($entityTypeManager) {
        $user = $entityTypeManager->getStorage('user')->load($uid);
    }
}
```
