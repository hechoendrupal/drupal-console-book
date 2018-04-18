# update:execute
विभागाची एक विशिष्ट सुधारणा N कार्य चालवा, किंवा सर्व कार्ये चालवा.

**वापर:**
```
drupal update:execute [arguments]
upex
updb
```

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
module | मॉड्यूलचे नाव.
update-n | commands.update.execute.options.update-n

## उदाहरणे
* अस्तित्व अद्यतनित करा.
```
drupal update:execute
```
* Execute updates for system module
```
drupal update:execute system
```
