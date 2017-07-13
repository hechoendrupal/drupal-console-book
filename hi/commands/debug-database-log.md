# debug:database:log
एप्लीकेशन के लिए वर्तमान लॉग इवेंट्स को प्रदर्शित करे

**commands.generate.doc.gitbook.messages.usage:**
```
$ drupal debug:database:log [arguments] [options]
$ dbb  
```

## commands.generate.doc.gitbook.messages.options
commands.generate.doc.gitbook.messages.option | commands.generate.doc.gitbook.messages.details
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id
--asc | List events in ascending order
--limit | एक विशिष्ट संख्या को सीमा परिणाम
--offset | एक सीमा का शुरूआती पॉइंट्स
--yml | Print in a yml style

## commands.generate.doc.gitbook.messages.arguments
commands.generate.doc.gitbook.messages.argument | commands.generate.doc.gitbook.messages.details
---------|-------------
event-id | DBLog इवेंट आईडी
