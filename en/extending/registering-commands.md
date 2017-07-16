# Registering Commands

To make the console commands available within a Drupal installation, you will need to:

1. Create a `Command` directory inside your module, theme, profile i.e. `src/Command` and create a `PHP` file suffixed with `Command.php` i.e. `DefaultCommand.php` for each command that you want to provide.
2. Register your command as a service using the `console.services.yml` file at the root of your extension (module, theme, profile) and tag service definition as `drupal.command`.
```
services:
  example.example_default:
    class: Drupal\example\Command\DefaultCommand`
    arguments: ['@entity_type.manager']
    tags:
      - { name: drupal.command }
```
