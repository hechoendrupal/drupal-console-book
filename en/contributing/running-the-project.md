# Running the project
In order to contribute you will need a working Drupal site linked to the packages you cloned and forked.

## Execute the automated process
DrupalConsole provides you with a command to take care of all this process for you.
```
drupal develop:contribute \
--drupal=/path/to/drupal8.dev \
--code=/Users/username/drupal-console-code/
```

The option `--drupal` is the directory where the new drupal site will be created and the option `--code` is the parent directory where the different DrupalConsole repositories were cloned.

> NOTE: You must execute `drupal init` before in order to copy the `~/.console/chain/develop-contribute.yml` on your local system.

## Execute all the steps manually
If you want to execute all the steps manually you can follow the instructions below:

### Download Drupal and DrupalConsole
```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

### Download the Drupal Console Develop package
```
composer require drupal/console-develop --dev
```

### Install Drupal using SQLite
```
drupal site:install standard --db-type="sqlite" --no-interaction
```
> NOTE: You can install drupal using MySQL by executing the `site:install` command and answering the questions from the interactive mode.

### Create a symbolic link between Drupal and forked repositories
```
drupal develop:create:symlinks \
--code-directory=/Users/username/drupal-console-code/
```

## Downloading additional Drupal Console language or packages

If you want to contribute translating Drupal Console to [Spanish](https://github.com/hechoendrupal/drupal-console-es) you should:

1.- Download it on the drupal site by executing the following command.

```
composer require drupal/console-es
```

2.- Fork and clone the repo to your local directory.

3.- Execute the `develop:create:symlinks` again, to create symlinks including the recently added package.

This applies for additional languages and packages i.e [drupal/console-yaml](https://github.com/weknowinc/drupal-console-yaml).

## Wrapping up

Now you can do the required changes and start contributing, commit you changes, push code to your forked repositories and create a Pull Request to the respective repository.

Happy coding ... thanks for contributing to Drupal Console.
