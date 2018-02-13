# What is a chain command

A `chain` command help you to automate command execution, allowing you to define an external YAML file containing the definition name, option and arguments of several commands and execute that list based on the sequence defined in the file.

## Chain command features:

### Discovery of YAML files
Chains commands are discovered from the following path(s): 
* **Globally** `~/.console/chain` 
* **Per site** `path/to/site/console/chain`

### Define placeholders
You can define placeholders using `{{name}}` and you can pass a key=value from the CLI as command option `--name=[VALUE]` when executing the command.  
```
commands:
  # Create Drupal project using DrupalComposer
  - command: exec
    arguments:
      bin: composer create-project {{repository}} {{directory}} --prefer-dist --no-progress --no-interaction
  # Install Drupal
  - command: exec
    arguments:
      bin: drupal site:install {{profile}} --root={{directory}} --db-type="sqlite" --no-interaction
  # Start PHP built-in server
  - command: exec
    arguments:
      bin: drupal server --root={{directory}}
```

### Set default values for placeholders
You can use the `variables` section to define default values for placeholders.
```
vars:
  repository:
    - drupal-composer/drupal-project:8.x-dev
    - acquia/lightning-project
    - acquia/reservoir-project
  profile: standard
```

You can define placeholders as single value or as an array. This definition will be used to decide the type of question generated when executing this command using the interactive mode.

### Read environment variables:
You can read environment variables using `{{ env("ENVIRONMENT_VAR_NAME") }}`.
```
command:
  name: site:install:env
  description: 'Install site using environment placeholders'
commands:
  # Install Drupal
  - command: site:install
    options:
      langcode: en
      db-type: '{{ env("DATABASE_TYPE") }}'
      db-host: '{{ env("DATABASE_HOST") }}'
      db-name: '{{ env("DATABASE_NAME") }}'
      db-user: '{{ env("DATABASE_USER") }}'
      db-pass: '{{ env("DATABASE_PASSWORD") }}'
      db-port: '{{ env("DATABASE_PORT") }}'
      site-name: 'Drupal 8 site'
      site-mail: admin@example.org # default email
      account-name: admin # default account
      account-mail: admin@example.org # default email
      account-pass: admin # default pass
    arguments:
      profile: 'standard'
```
All of the required environment variables used on a chain command definition are mandatory.
