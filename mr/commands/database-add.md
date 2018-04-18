# database:add
Settings.php वर एक डेटाबेस जोडा.

**वापर:**
```
drupal database:add [options]
dba
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--database | डेटाबेसचे नाव.
--username | डेटाबेस वापरकर्तानाव.
--password | डेटाबेस संकेतशब्द.
--prefix | डेटाबेस उपसर्ग.
--host | डेटाबेस होस्ट पत्ता.
--port | डेटाबेस होस्ट पोर्ट.
--driver | डेटाबेस ड्राइव्हर.

## उदाहरणे
* Settings.php एक डेटाबेस जोडा.
```
drupal database:add \
  --database=DATABASE \
  --username=USERNAME \
  --password=PASSWORD
```
