# generate:profile
प्रोफाइल उत्पन्न करा.

**Usage:**
```
drupal generate:profile [options]
gpr
```

## Available options
Option | Details
-------|-------------
--profile | प्रोफाइल नाव.
--machine-name | मशीनचे नाव (केवळ लोअरकेस आणि अंडरस्कोर)
--description | प्रोफाइल वर्णन.
--core | कोर आवृत्ती.
--dependencies | स्वल्पविरामाने विभक्त केलेले मॉड्यूल अवलंबन (i.ई संदर्भ, पॅनेल)
--themes | commands.generate.profile.options.themes
--distribution | वितरण नाव.

## Examples
* Generate a profile specifying the profile name, the machine name, a description, the core and its module dependencies
```
drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"
```
