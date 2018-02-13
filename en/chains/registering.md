# Registering as regular commands

Chains definition can contain metadata that make them discovered and registered by DrupalConsole so they can be executed as any other regular command.

To register as regular command you need to add a `command` section containing `name` and `description`.

```
command:
  name: build
  description: 'Build site'
vars:
  profile:
    - standard
    - minimal
commands:
  # Install site
  - command: site:install
    options:
      force: true
    arguments:
      profile: "{{ profile }}"
  # Import configuration
  - command: config:import
    options:
      skip-uuid: true
  # Rebuild caches.
  - command: cache:rebuild
    arguments:
        cache: all

```

After adding the command section you should see the new `build` command listed when running the `list` command.
