# Update project
Drupal 8 is under heavy development, to keep in sync with the latest changes. The easiest and recommended way of updating Drupal Console is using the self-update command.

## Depending on the installation method:

### Installed globally (and renamed to "drupal"):
```
$ drupal self-update
```

### Installed globally (using composer):
```
$ composer global update drupal/console:@stable
```

### Installed locally (running from directory where the console.phar has been downloaded):
```
$ php console.phar self-update
```

