# module:update
Update core, module or modules in the application

**प्रयोग:**
```
$ drupal module:update [arguments] [options]
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--composer | Update the module using Composer
--simulate | Simulate the update process with Composer

## उपलब्ध तर्क
तर्क | विवरण
---------|-------------
module | Module or modules to be updated should be separated by a space. Leave empty for updating the core and all your modules managed by Composer.
