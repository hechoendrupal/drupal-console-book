# generate:module
मॉड्यूल उत्पन्न करा.

**वापर:**
```
drupal generate:module [options]
gm
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूल नाव.
--machine-name | मशीनचे नाव (केवळ लोअरकेस आणि अंडरस्कोर)
--module-path | मॉड्यूलचा मार्ग.
--description | मॉड्यूल वर्णन.
--core | कोर आवृत्ती.
--package | मॉड्यूल पॅकेज
--module-file | एक .module फाइल जोडा
--features-bundle | दिलेल्या वैशिष्ट्ये बंडलचे नाव वापरून मॉड्यूल म्हणून वैशिष्ट्य म्हणून परिभाषित करा.
--composer | एक composer.json फाईल जोडा.
--dependencies | स्वल्पविरामाने विभक्त केलेले मॉड्यूल अवलंबन (i.ई संदर्भ, पॅनेल)
--test | चाचणी श्रेणी उत्पन्न करा.
--twigtemplate | थीम टेम्पलेट उत्पन्न करा.

## उदाहरणे
* मॉड्यूल नाव, मशीनचे नाव, पथ, त्याचे वर्णन, ड्रापल कोर आणि संकुल नाव निर्देशीत केलेले मॉड्यूल उत्पन्न करा. या उदाहरणात संगीतकार फाइल, युनिट टेस्ट आणि टिम टेम्प्लेट सुद्धा उत्पन्न केले जातात.
```
drupal generate:module  \
  --module="modulename"  \
  --machine-name="modulename"  \
  --module-path="/modules/custom"  \
  --description="My Awesome Module"  \
  --core="8.x"  \
  --package="Custom"  \
  --module-file  \
  --composer  \
  --test  \
  --twigtemplate
```
