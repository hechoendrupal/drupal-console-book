# generate:event:subscriber
एक घटना ग्राहक उत्पन्न करें

**Usage:**
```
drupal generate:event:subscriber [options]
ges
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--name | Service name
--class | Class name
--events | घटनाओ को container से लोड करें।
--services | सर्विसेज़ को container से लोड करें।

## Examples
* Generate an event subscriber specifying the module name, its name, the class and the events to subscribe
```
drupal generate:event:subscriber  \
  --module="modulename"  \
  --name="modulename.default"  \
  --class="DefaultSubscriber"  \
  --events='kernel_request'
```
