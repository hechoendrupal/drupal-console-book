# debug:database:log
एप्लीकेशन के लिए वर्तमान लॉग इवेंट्स को प्रदर्शित करे

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
ws
```

## Available options
Option | Details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | एक विशिष्ट संख्या को सीमा परिणाम
--offset | एक सीमा का शुरूआती पॉइंट्स
--yml | Print in a yml style

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog इवेंट आईडी

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
