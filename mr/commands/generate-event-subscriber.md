# generate:event:subscriber
एक कार्यक्रम ग्राहक उत्पन्न करा.

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | मॉड्यूलचे नाव.
--name | commands.generate.service.options.name
--class | वर्ग नाव
--events | कंटेनर मधून इव्हेंट्स भरा.
--services | कंटेनर मधून सेवा भरा.

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
