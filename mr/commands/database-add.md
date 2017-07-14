# database:add
Settings.php वर एक डेटाबेस जोडा.

**application.gitbook.messages.usage:**
```
drupal database:add [options]
dba
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--database | डेटाबेसचे नाव.
--username | डेटाबेस वापरकर्तानाव.
--password | डेटाबेस संकेतशब्द.
--prefix | डेटाबेस उपसर्ग.
--host | डेटाबेस होस्ट पत्ता.
--port | डेटाबेस होस्ट पोर्ट.
--driver | डेटाबेस ड्राइव्हर.

## application.gitbook.messages.examples
* Settings.php एक डेटाबेस जोडा.
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
