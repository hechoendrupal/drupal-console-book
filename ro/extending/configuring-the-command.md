# Configuring the command.

You must provide a`configure` method containing the configuration of the command as name, arguments, options, etc.
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
