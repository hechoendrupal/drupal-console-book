# Configurando el comando.

Debes proveer un método `configure` que contenga la configuración del comando como nombre, argumentos, opciones, etc.
```
    /**
     * {@inheritdoc}
     */
    protected function configure()
    {
        $this
            ->setName('user:login:url')
            ->setDescription($this->trans('commands.user.login.url.description'))
            ->addArgument(
                'uid',
                InputArgument::REQUIRED,
                $this->trans('commands.user.login.url.options.uid'),
                null
            );
    }
```
