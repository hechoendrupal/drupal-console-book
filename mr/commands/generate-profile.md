# generate:profile
प्रोफाइल उत्पन्न करा.

**वापर:**
```
drupal generate:profile [options]
gpr
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--profile | प्रोफाइल नाव.
--machine-name | मशीनचे नाव (केवळ लोअरकेस आणि अंडरस्कोर)
--profile-path | The path of the profile
--description | प्रोफाइल वर्णन.
--core | कोर आवृत्ती.
--dependencies | स्वल्पविरामाने विभक्त केलेले मॉड्यूल अवलंबन (i.ई संदर्भ, पॅनेल)
--themes | the theme name
--distribution | वितरण नाव.

## उदाहरणे
* प्रोफाइल नाव, मशीन नाव, वर्णन, कोर आणि त्याची मॉड्यूल अवलंबन निर्देशीत करतेवेळी प्रोफाइल उत्पन्न करा.
```
drupal generate:profile  \
  --profile="NewProfileName"  \
  --machine-name="newprofilename"  \
  --description="My Useful Profile"  \
  --core="8.x"  \
  --dependencies="modulename"
```
