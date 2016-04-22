# database:log:clear
DBLog टेबल से इवेंट्स निकालें, फिल्टर उपलब्ध हैं

**प्रयोग:**
```
$ drupal database:log:clear [arguments] [options]
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--type | Filter events by a specific type
--severity | Filter events by a specific level of severity
--user-id | Filter events by a specific user id

## उपलब्ध तर्कों
तर्क | विवरण
---------|-------------
event-id | DBLog event ID
