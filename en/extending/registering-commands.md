# Registering Commands

To make the console commands available within a Drupal installation, you will need to register your Command Class as a service using the `console.services.yml` file at the root of your extension (module, theme, profile) and tag service definition as `drupal.command`.
```
services:
  example.example_default:
    class: Drupal\example\Command\DefaultCommand`
    arguments: ['@entity_type.manager']
    tags:
      - { name: drupal.command }
```
> NOTE: The `arguments` section on the service definition is optional and used only if you will be injecting services from the container on your command.