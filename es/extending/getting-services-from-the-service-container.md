# Obteniendo Servicios del Contenedor de Servicios

Al usar `ContainerAwareCommand` como la clase base para el comando (en lugar de la más básica `Command`), tienes acceso al contenedor de servicios. En otras palabras, tienes acceso a cualquier servicio provisto por el contenedor de Drupal usando el método `getService`.

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
