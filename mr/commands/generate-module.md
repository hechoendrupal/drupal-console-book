# generate:module
मॉड्यूल उत्पन्न करा.

**Usage:**
```
drupal generate:module [options]
gm
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूल नाव.
--machine-name | मशीनचे नाव (केवळ लोअरकेस आणि अंडरस्कोर)
--module-path | मॉड्यूलचा मार्ग.
--description | मॉड्यूल वर्णन.
--core | कोर आवृत्ती.
--package | मॉड्यूल पॅकेज
--module-file | एक .module फाइल जोडा
--features-bundle | दिलेल्या वैशिष्ट्ये बंडलचे नाव वापरून मॉड्यूल म्हणून वैशिष्ट्य म्हणून परिभाषित करा.
--composer | एक composer.json फाईल जोडा.
--dependencies | स्वल्पविरामाने विभक्त केलेले मॉड्यूल अवलंबन (i.ई संदर्भ, पॅनेल)
--test | चाचणी श्रेणी उत्पन्न करा.
--twigtemplate | थीम टेम्पलेट उत्पन्न करा.

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
