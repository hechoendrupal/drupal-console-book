# debug:database:log
अनुप्रयोगासाठी वर्तमान लॉग इव्हेंट प्रदर्शित करा.

**application.gitbook.messages.usage:**
```
drupal debug:database:log [arguments] [options]
dbb
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--type | विशिष्ट प्रकाराद्वारे इव्हेंट फिल्टर करा.
--severity | एका विशिष्ट स्तर तीव्रतेने इव्हेंट फिल्टर करा.
--user-id | विशिष्ट वापरकर्ता आयडी द्वारे इव्हेंट फिल्टर करा.
--asc | चढत्या क्रमाने कार्यक्रमांची सूची करा.
--limit | एका विशिष्ट क्रमांकासाठी परिणाम मर्यादित करा.
--offset | मर्यादा प्रारंभ करत आहे.
--yml | एक YML शैली मुद्रण

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
event-id | DBLog इव्हेंट आयडी
