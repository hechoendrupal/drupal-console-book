# How to download, install and serve Drupal 8

The easiest way to try Drupal 8 in your local machine is by executing the `quick:start` command.

```
drupal quick:start
```

The content of the provided `~/.console/chain/quick-start.yml` file is:
```
# How to use
# quick:start --directory="/path/to/drupal-project/"
# quick:start --directory="/path/to/drupal-project/" --profile="minimal"
# quick:start --repository="acquia/lightning-project:^8.1" --directory="/path/to/drupal-project/" --profile="lightning"
command:
  name: quick:start
  description: 'Download, install and serve a new Drupal project'
vars:
  repository:
    - drupal-composer/drupal-project:8.x-dev
    - acquia/lightning-project
    - acquia/reservoir-project
  profile: standard
commands:
  # Create Drupal project using DrupalComposer
  - command: exec
    arguments:
      bin: composer create-project %{{repository}} %{{directory}} --prefer-dist --no-progress --no-interaction
  # Install Drupal
  - command: exec
    arguments:
      bin: drupal site:install %{{profile}} --root=%{{directory}} --db-type="sqlite" --no-interaction
  # Start PHP built-in server
  - command: exec
    arguments:
      bin: drupal server --root=%{{directory}}ß
```

The previous configuration will execute several commands, in this case commands that will download and install Drupal using SQLite, and finally start the PHP's built in server, now you only need to open your browser and point it to 127.0.0.1:8088.
