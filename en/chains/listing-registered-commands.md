# Listing registered commands

You can debug the discovered chain commands using the `debug:chain` command.  
```
 Directory /path/to/drupal8.dev/vendor/drupal/console-core/config/chain/
 ------------------------ --------------------
  File name.               Command name.
 ------------------------ --------------------
  develop-contribute.yml   develop:contribute
  quick-start.yml          quick:start
  site-new.yml             site:new
 ------------------------ --------------------
  
  Directory /path/to/drupal8.dev/console/chain/
 -------------------------- ----------------------
  File name.                 Command name.
 -------------------------- ----------------------
  build.yml                  build
  cache-rebuild-custom.yml   cache:rebuild:custom
  custom-test.yml
 -------------------------- ----------------------
```

For any non-registered chain command discovered you will see a message like this.
```
/path/to/drupal8.dev/console/chain/custom-test.yml
 * You should register your chain file as command by providing metadata, more info at:
   https://docs.drupalconsole.com/en/chains/registering.html
```