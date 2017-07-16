# Using the project

Drupal Console provides two types of commands.

1. **Global Launcher Commands:** These commands can run outside of a Drupal 8 site root.
2. **Per-site Commands:** These commands must be run within a Drupal 8 site root.

### Executing Drupal Console outside a Drupal site root 
You can run Drupal Console from any directory on your system by using the `--root` option to define the Drupal root to be use in the command execution. 
```
drupal --root=/var/www/drupal8.dev cr all
```

**NOTE:** Possible messages when executing Drupal Console outside a Drupal site root and no `--root` option provided.

When running the project outside of a Drupal 8 site root, the following message will be shown.  
> In order to list all of the available commands, you should run this inside a drupal root directory.

When running the project within of a Drupal 8 site root, but site is not yet installed, the following message will be shown.
> In order to list all of the available commands you should install drupal first.

If you already have an existing Drupal 8 site and have installed the global Launcher using the instructions in [2.2](../getting/launcher.md), you will still need to install it into the Drupal site using instructions at [2.1](../getting/composer.md) section.
