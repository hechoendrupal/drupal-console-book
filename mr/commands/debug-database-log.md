# debug:database:log
अनुप्रयोगासाठी वर्तमान लॉग इव्हेंट प्रदर्शित करा.

**Usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## Available options
Option | Details
-------|-------------
--type | विशिष्ट प्रकाराद्वारे इव्हेंट फिल्टर करा.
--severity | एका विशिष्ट स्तर तीव्रतेने इव्हेंट फिल्टर करा.
--user-id | विशिष्ट वापरकर्ता आयडी द्वारे इव्हेंट फिल्टर करा.
--asc | चढत्या क्रमाने कार्यक्रमांची सूची करा.
--limit | एका विशिष्ट क्रमांकासाठी परिणाम मर्यादित करा.
--offset | मर्यादा प्रारंभ करत आहे.
--yml | एक YML शैली मुद्रण

## Available arguments
Argument | Details
---------|-------------
event-id | DBLog इव्हेंट आयडी

## Examples
* List all the entries on the log
```
drupal debug:database:log
```
* List specific log entry by Event ID
```
drupal debug:database:log 21228
```
