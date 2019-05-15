# config:import
Import configuration to current application.

**Usage:**
```
drupal config:import [options]
ci
```

## Available options
Option | Details
-------|-------------
--file | Path to an archive file of configuration to import.
--directory | Path to a directory of configuration to import.
--remove-files | Remove files after synchronization.
--skip-uuid | commands.config.import.options.skip-uuid

## Examples
* Provide a configuration file
```
drupal config:import \
  --file=/path/to/config/file
```
* Provide a configuration directory
```
drupal config:import  \
  --directory=/path/to/config/dir
```

## How to install Drupal 8 from an existing configuration
If you want to restore an existing site, you will need to run
the following command to configure Drupal Console so that it can
restore a website that was previously installed.

```
drupal settings:set overrides.config.skip-validate-site-uuid true
```

See more details here https://weknowinc.com/blog/how-install-drupal-8-existing-configuration
