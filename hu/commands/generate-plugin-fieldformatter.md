# generate:plugin:fieldformatter
Mezőformázó bővítmény létrehozása

**Usage:**
```
drupal generate:plugin:fieldformatter [options]
gpff
```

## Available options
Option | Details
-------|-------------
--module | A modul neve.
--class | Bővítmény osztályneve
--label | Bővítmény felirata
--plugin-id | Bővítmény azonosítója
--field-type | Mezőtípus, amivel a bővítmény használható

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
