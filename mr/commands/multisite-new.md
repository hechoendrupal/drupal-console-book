# multisite:new
Sets up the files for a new multisite install.

**Usage:**
```
drupal multisite:new [arguments] [options]
mun
```

## Available options
Option | Details
-------|-------------
--copy-default | विद्यमान साइट डीफॉल्ट इन्स्टॉलेशन मधून कॉपी करतात.

## Available arguments
Argument | Details
---------|-------------
directory | "sites" या निर्देशिकेचे नाव जे तयार करायला हवे.
uri | साइट यूआरआय sites.php वर जोडण्यासाठी.

## Examples
* Set up files for a multisite install specifying destination path and uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
