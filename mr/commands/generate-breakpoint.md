# generate:breakpoint
ब्रेकपॉईंट उत्पन्न करा.

**वापर:**
```
drupal generate:breakpoint [options]
gb
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--theme | थीम नाव
--breakpoints | ब्रेकपॉइंट

## उदाहरणे
* थीम, एक ब्रेकपॉईंट नाव, त्याचे लेबल, मीडिया क्वेरी, त्याचे वजन आणि मल्टिप्लायर निर्दिष्ट करणारा ब्रेकपॉइंट उत्पन्न करा.
```
drupal generate:breakpoint  \
  --theme="classy"  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
