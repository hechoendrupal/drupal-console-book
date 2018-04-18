# generate:plugin:mail
एक प्लगइन मेल उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:mail [options]
gpm
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--class | प्लगइन वर्ग नाव.
--label | प्लगइन लेबल.
--plugin-id | प्लगिन आयडी.
--services | कंटेनर मधून सेवा भरा.

## उदाहरणे
* मॉड्यूल नाव, वर्ग, त्याचे लेबल आणि प्लगिनआयडीनिर्दिष्ट करणारा ईमेल प्लगइन उत्पन्न करा.
```
drupal generate:plugin:mail  \
  --module="modulename"  \
  --class="HtmlFormatterMail"  \
  --label="Html formatter mail"  \
  --plugin-id="html_formatter_mail"
```
