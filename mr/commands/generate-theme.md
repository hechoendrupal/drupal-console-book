# generate:theme
थीम उत्पन्न करा.

**वापर:**
```
drupal generate:theme [options]
gt
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--theme | थीमचे नाव.
--machine-name | मशीनचे नाव (केवळ लोअरकेस आणि अंडरस्कोर).
--theme-path | थीमचा मार्ग.
--description | थीम वर्णन.
--core | कोर आवृत्ती.
--package | थीम पॅकेज
--global-library | जागतिक शैली लायब्ररी नाव.
--libraries | Libraries
--base-theme | मूलभूत थीम (उदा. सुंदर, स्थिर)
--regions | विभाग
--breakpoints | ब्रेकपॉइंट

## उदाहरणे
* थीमविना आणि थीमचे नाव, त्याचे मशीन नाव, थीम पथ, वर्णन, Drupal core, पॅकेजचे नाव आणि जागतिक लायब्ररी दर्शविणार्या कोणत्याही बिंदूविनाहित थीम उत्पन्न करा.
```
drupal generate:theme  \
  --theme="AnotherTheme"  \
  --machine-name="anothertheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="PackageName"  \
  --global-library="global-styling"  \
  --base-theme="false"
```
* परिभाषित केलेल्या दोन प्रदेशांसह स्थिर थीमवर थीम बेस उत्पन्न करा आणि थीम नाव, त्याचे मशीन नाव, थीम पथ, वर्णन, Drupal core, पॅकेज नाव, एक जागतिक लायब्ररी, त्याचे बेस, क्षेत्र आणि ब्रेकपॉइंट निर्दिष्ट करणारे एक ब्रेकपॉईंट उत्पन्न करा.
```
drupal generate:theme  \
  --theme="MyTheme"  \
  --machine-name="mytheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="MyThemePackage"  \
  --global-library="global-styling"  \
  --base-theme="stable"  \
  --regions='"region_name":"Content", "region_machine_name":"content"'  \
  --regions='"region_name":"Panel", "region_machine_name":"panel"'  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
