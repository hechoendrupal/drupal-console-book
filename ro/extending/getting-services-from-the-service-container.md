# Getting Services from the Service Container

By using `ContainerAwareCommand` as the base class for the command (instead of the more basic `Command`), you have access to the service container. In other words, you have access to any configured service using the provided `getService` method.

```
protected function execute(InputInterface $input, OutputInterface $output)
{
    $uid = $input->getArgument('uid');
    $entityManager = $this->getService('entity.manager');
    if ($entityManager) {
        $user = $entityManager->getStorage('user')->load($uid);
    }
}
```
