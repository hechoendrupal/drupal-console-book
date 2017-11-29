# Получение сервисов из контейнера сервисов

Используя `ContainerAwareCommand` как базового класса для ваших команд (вместо более простого `Command`), у вас есть доступ к контейнеру сервисов. Другими словами, у вас есть доступ к любому сконфигурированному сервису, используя предоставленный метод `getService`.

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
