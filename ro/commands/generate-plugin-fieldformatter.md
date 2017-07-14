# generate:plugin:fieldformatter
Generează extensia de formatare a câmpului.

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | Numele Modulului.
--class | Numele clasei pentru extensie
--label | Eticheta extensiei
--plugin-id | ID-ul extensiei
--field-type | Tipul câmpului cu, care extensia poate fi folosită

## Examples
* Generate a a text field formatter plugin specifying the module name, the class, the label its plugin id and the field type
```
drupal generate:plugin:fieldformatter  \
  --module="modulename"  \
  --class="ExampleFieldFormatter"  \
  --label="Example field formatter"  \
  --plugin-id="example_field_formatter"  \
  --field-type="text"
```
