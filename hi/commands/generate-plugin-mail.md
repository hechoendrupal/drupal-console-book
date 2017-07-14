# generate:plugin:mail
एक प्लगइन मेल उत्पन्न करें

**Usage:**
```
drupal generate:plugin:mail [options]
gpm
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--class | प्लगइन क्लास नाम
--label | प्लगइन लेबल
--plugin-id | प्लगइन आईडी
--services | सर्विसेज़ को container से लोड करें।

## Examples
* Generate an email plugin specifying the module name, the class, its label and the plugin id
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
