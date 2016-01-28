# विन्यास फाइल कॉपी कैसे करें
आप Drupal कंसोल स्थापित करने के बाद क्या करना चाहिए पहली कार्य निष्पादित करने के लिए है `init` कमाण्ड. इस कमाण्ड को चलाने पर परियोजना विन्यास फाइल आपकी `~/.console/` निर्देशिका में कॉपी की जाएँगी| इन नकल फाइल पर मानों अधिभावी आप DrupalConsole व्यवहार कैसे बदल सकते है|

 ```
 $ drupal init [--override]
 ```

### कौनसी फाइल्स कॉपी की जाएगी जब `init` कमाण्ड चलेगी|
```
 ~/.console/
 ├── aliases.yml
 ├── chain
 │   ├── quick-start.yml
 │   └── sample.yml
 ├── config.yml
 ├── console.rc
 ├── drupal.fish
 └── sites
     └── sample.yml
```