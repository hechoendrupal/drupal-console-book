# Getting Services from the Service Container

You can access services from the service container by:

* Injecting services to the command Class

Registering your Command class at the `console.services.yml` file.
```
services:
  example.example_default:
    class: Drupal\example\Command\DefaultCommand`
    arguments: ['@entity_type.manager']
    tags:
      - { name: drupal.command }
```

Adding a new protected property and passing the service using the `__construct` method.
```
  /**
   * The $entityTypeManager definition.
   *
   * @var EntityTypeManager
   */
  protected $entityTypeManager;

  /**
   * Constructs a new DefaultCommand object.
   */
  public function __construct(EntityTypeManager $entity_type_manager) {
    $this->entityTypeManager = $entity_type_manager;
    parent::__construct();
  }
```

* Using the ContainerAwareCommandTrait on your class.

By doing this you have access to the service container, in other words, you have access to any configured service using the provided `get` method.

```
protected function execute(InputInterface $input, OutputInterface $output)
{
    $uid = $input->getArgument('uid');
    $entityManager = $this->get('entity_type.manager');;
    if ($entityManager) {
        $user = $entityManager->getStorage('user')->load($uid);
    }
}
```
