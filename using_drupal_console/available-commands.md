# Available Drupal Console Commands

**Note:** Drupal Console commands *must* be run from the root of a Drupal 8 installation.

Drupal Console Command | Details
------------ | -------------
[drush](drush.md) | Runs Drush from Drupal Console
help | Displays help for a Drupal Console command
[init](init.md) | Copies configuration files to user home directory.
list | Lists all Drupal Console commands
self-update | Updates Drupal Console to the latest version
**cache**  |
[cache:rebuild](cache-rebuild.md)  | Rebuilds and clears all site caches
**config**  |
 [config:debug](config-debug.md)  |   Shows the current configuration
 [config:edit](config-edit.md)  |    Allows editing the selected configuration
 [config:export](config-export.md)  |  Exports current application configuration
 [config:override](config-override.md)  | Overrides config value in active configuration
**container**  |
 [container:debug](container-debug.md) | Displays current services for an application
**generate**  |
 [generate:authentication:provider](generate-authentication-provider.md)  |   Generates an Authentication Provider
 [generate:command](generate_command.md)  |   Generate commands for the console
 [generate:controller](generate_controller.md)  | Generate & Register a controller
 [generate:entity:config](generate-entity-config.md)  | Generates a new "EntityConfig"
 [generate:entity:content](generate-entity-content.md)   | Generates a new "EntityContent"
 [generate:form:config](generate-form-config.md)   |    Generates a new "ConfigFormBase"
 [generate:module](generate_module.md)  |    Generates a new module.
 [generate:permissions](generate_permissions.md)   |    Generate module permissions
 [generate:plugin:block](generate-plugin-block.md)   |   Generates a plugin block
 [generate:plugin:imageeffect](generate-plugin-imageeffect.md)  | Generates an image effect plugin
 [generate:plugin:rest:resource](generate-plugin-rest-resource.md)  | Generates a REST resource plugin
 [generate:plugin:rulesaction](generate-plugin-rulesaction.md)  | Generates a Rules action plugin
 [generate:service](generate_service.md)  | Generates a service
**migrate**  |
 migrate:debug  |  Display current migration available for the application
 migrate:execute  |  Execute a migration available for application
**module**  |
 module:debug  |   Displays current modules available for the application
 module:download  |   Downloads a module or modules in the application
 module:install  | Installs a module or modules in the application
 module:uninstall  |   Uninstalls a module or modules in the application
**rest**  |
 rest:debug  |     Display current REST resource(s) for the application
 rest:disable  |   Disables a REST resource for the application
 rest:enable  |    Enables a REST resource for the application
**router**  |
 router:debug  |   Displays current routes for the application
 router:rebuild  | Rebuilds routes for the application
**site**  |
 site:maintenance  |   Switches site into maintenance mode
 site:mode  |      Switches system performance configuration
 site:status  |    Displays current Drupal installation status
**test**  |
 test:debug  |     Lists unit tests available for the application
