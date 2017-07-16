# Running the project
In order to contribute you will need a working Drupal site linked to the packages you cloned and forked.

## Execute the automated process
We provide you with a command to take care of all this process and setup for you.
```
drupal console:contribute \
--drupal=/path/to/drupal8.dev \
--code=/Users/username/drupal-console-code/
```
> NOTE: You must execute `drupal init` before in order to copy the `~/.console/chain/console-contribute.yml` on your local system.

## Execute all the steps manually
If you want to execute all the steps manually you can follow instructions below: 

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

### Create a symbolic link between Drupal and forked repositories
```
drupal develop:contribute \
--code-directory=/Users/username/drupal-console-code/
```

> NOTE: You can install drupal using MySQL by executing the `site:install` command and answering the questions from the interactive mode.
