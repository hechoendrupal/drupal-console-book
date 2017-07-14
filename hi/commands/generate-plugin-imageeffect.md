# generate:plugin:imageeffect
छवि प्रभाव प्लगिन उत्पन्न करें

**Usage:**
```
drupal generate:plugin:imageeffect [options]
gpie
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगिन का क्लास नाम
--label | प्लगिन उप-शीर्षक
--plugin-id | प्लगिन id
--description | प्लगिन विवरण

## Examples
* Generate a image effect plugin specifying the module name, the class, its label, the plugin id and a description
```
drupal generate:plugin:imageeffect  \
  --module="modulename"  \
  --class="DefaultImageEffect"  \
  --label="Default image effect"  \
  --plugin-id="default_image_effect"  \
  --description="My Image Effect"
```
