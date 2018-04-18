# generate:profile
प्रोफाइल उत्पन्न करे.

**Usage:**
```
drupal generate:profile [options]
gpr
```

## Available options
Option | Details
-------|-------------
--profile | प्रोफाइल नाम
--machine-name | मशीन का नाम (लोअरकेस और अंडरस्कोर केवल)
--profile-path | The path of the profile
--description | प्रोफाइल विवरण
--core | कोर संस्करण
--dependencies | मॉड्यूल निर्भरता अल्पविराम से अलग किया जाता है (जेसे context, panels)
--themes | the theme name
--distribution | वितरण नाम

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
