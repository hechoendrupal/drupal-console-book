# generate:doc:gitbook
The **generate:doc:gitbook** command Generate documentations for Commands

**Usage:**
```
$ drupal generate:doc:gitbook [arguments] [options] 
$ gdg  
```

## Available options
Option | Details
-------|-------------
--path | The path to render the documentation
--help | इस सहायता संदेश को दिखाएँ
--quiet | कोई संदेश ना दिखाएँ
--verbose | संदेशों के शब्दाडंबर को बढ़ाएं: सामान्य निर्गम के लिए १, अधिक शब्दबहुल के लिए २ और डिबग के लिए ३
--version | अनुप्रयोग संस्करण दिखाएँ
--ansi | ANSI परिणाम अनिवार्य करें
--no-ansi | ANSI निगम अक्षम करें
--no-interaction | कोई वार्तालाप प्रशन ना पूछें
--root | कमाण्ड चलाने के लिए Drupal रूट परिभाषित करें
--env | पर्यावरण का नाम।
--no-debug | डिबग विधि को बंद कर देता है।
--learning | शब्दबहुल कोड उत्पन्न करें।
--generate-chain | निष्पादन विकल्प में प्रिंट और तर्क को YAML आउटपुट के रूप में श्रृंखला कमांड में इस्तेमाल किया जाएगा
--generate-inline | निष्पादन विकल्प में प्रिंट और तर्क को इनलाइन कॉल के रूप में भविष्य में उपयोग किया जाएगा
--generate-doc | application.console.arguments.generate-doc
--target | application.console.arguments.target
--uri | URI of the Drupal site to use (for multisite environments or when running on an alternate port)

## Available arguments
Argument | Details
---------|-------------
command | चलने वाली कमाण्ड
