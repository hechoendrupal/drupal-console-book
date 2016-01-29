# How to download, install and serve Drupal 8

The easiest way to try Drupal 8 in your local machine is by executing the `chain` command and pass the option `--file=~/.console/chain/quick-start.yml` as shown on the following example.

```
$ drupal chain --file=~/.console/chain/quick-start.yml
```
> NOTE: You must execute `drupal init` before in order to copy the `~/.console/chain/quick-start.yml` on your system.

The `chain` command helps you to automate command execution, allowing you to define an external YAML file containing the definition name, option and arguments of several commands and execute that list based on the sequence defined in the file.

The content of the provided `~/.console/chain/quick-start.yml` file is:
```
commands:
  - command: site:new
    arguments:
      directory: drupal8.dev
      version: 8.0.2
  - command: site:install
    options:
        langcode: en
        db-type: sqlite
        db-file: sites/default/files/.ht.sqlite
        site-name: 'Drupal 8 Quick Start'
        site-mail: admin@example.com
        account-name: admin
        account-mail: admin@example.com
        account-pass: admin
        generate-inline: true
    arguments:
        profile: standard
  - command: server
```

The previous configuration will execute several commands, in this case commands that will download and install Drupal using SQLite, and finally start the PHP's built in server, now you only need to open your browser and point it to 127.0.0.1:8088.

You can duplicate or make changes on the provided YAML file, to add commands for download modules `module:download`, install modules `module:install` , import configurations `config:import` and restore your database `database:restore` or any other command provided by DrupalConsole or a custom command by your own module.
