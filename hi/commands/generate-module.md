# generate:module
मोड्यूल उत्पन्न करें।

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम
--machine-name | यांत्रिक नाम (लोअरकेस और केवल अंडरस्कोर)
--module-path | मोड्यूल का पथ
--description | मोड्यूल का विवरण
--core | मूल संस्करण
--package | मोड्यूल पैकेज
--module-file | एक .module फ़ाइल जोड़ें
--features-bundle | Define module as feature using the given Features bundle name
--composer | composer.json फाइल डालें
--dependencies | मोड्यूल निर्भरता को अल्पविराम से विभाजित करें (अथवा context, panels)
--test | एक परीक्षण क्लास बनाएं
--twigtemplate | Generate theme template

## Examples
* Generate a module specifying the module name, machine name, the path, its description, drupal core and the package name. In this example the composer file, the unit test and twig template are generated too
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
