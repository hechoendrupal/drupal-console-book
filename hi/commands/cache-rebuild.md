# cache:rebuild
The **cache:rebuild** command सभी साइट caches को पुनर्निर्माण और साफ़ करें।

**प्रयोग:**
```
$ drupal cache:rebuild [arguments] 
$ cr  
```

## उपलब्ध तर्कों  
तर्क | विवरण
---------|-------------
cache | केवल एक विशेष cache साफ़ करें।

## उदाहरण
* Rebuild all caches
```
$ drupal cr all
```
* Rebuild discovery cache
```
$ drupal cr discovery
```
