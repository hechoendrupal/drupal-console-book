# user:password:reset
किसी विशेष उपभोगता का पासवर्ड रिसेट करें

**Usage:**
```
drupal user:password:reset [arguments]
upr
upsr
```

## Available arguments
Argument | Details
---------|-------------
user | User name/id
password | पासवर्ड टेक्स्ट फॉरमेट में

## Examples
* Update password specifying the user id and the new password
```
drupal user:password:reset  2 p455w0rd
```
* Update password specifying the user jmolivas and the new password
```
drupal user:password:reset jmolivas p455w0rd
```
