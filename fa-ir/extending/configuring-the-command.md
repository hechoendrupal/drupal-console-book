# پیکربندی دستور

شما باید یک متد `configure` را به منظور پیکربندی نام، آرگومان‌ها و گزینه‌های دستور خود فراهم کنید.
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
