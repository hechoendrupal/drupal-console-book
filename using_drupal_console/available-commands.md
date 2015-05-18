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
 [migrate:debug](migrate-debug.md)  |  Displays current migration available for the application
 [migrate:execute](migrate-execute.md)  |  Executes an available migration
**module**  |
 [module:debug](module-debug.md)  |   Displays current modules available for the application
 [module:download](module-download.md)  |   Downloads a module or modules in the application
 [module:install](module-install.md)  | Installs a module or modules in the application
 [module:uninstall](module-uninstall.md)  |   Uninstalls module(s) from the application
**rest**  |
 [rest:debug](rest-debug.md)  |     Display current REST resource(s) for the application
 [rest:disable](rest-disable.md)  |   Disables a REST resource for the application
 [rest:enable](rest-enable.md)  |    Enables a REST resource for the application
**router**  |
 [router:debug](router-debug.md)  |   Displays current routes for the application
 [router:rebuild](router-rebuild.md)  | Rebuilds routes for the application
**site**  |
 [site:maintenance](site-maintenance.md)  |   Switches site into maintenance mode
 [site:mode](site-mode.md)  |      Switches system performance configuration
 [site:status](site-status.md)  |    Displays current Drupal installation status
**test**  |
 [test:debug](test-debug.md)  |     Lists unit tests available for the application
