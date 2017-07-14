# create:users
अपने Drupal 8 एप्लीकेशन के लिए डमी यूजरस बनाएँ।

**application.gitbook.messages.usage:**
```
drupal create:users [arguments] [options]
cru
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | कितने भी यूजरस आप बना सकते है
--password | पासवर्ड क्रिएटेड यूजरस के लिए स्थापित किया जाता है
--time-range | कितनी अवधि में यूजरस दिनांकित किया जाना चाहिए

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
roles | रोल(स) का उपयोग यूजर क्रिएशन में किया जाता है।

## application.gitbook.messages.examples
* Provide the user role.
```
drupal create:users role
```
* Provide the number of users to create, password and time range to create.
```
drupal create:users role \
  --limit="5" \
  --password="usersnewpassword" \
  --time-range="1"
```
