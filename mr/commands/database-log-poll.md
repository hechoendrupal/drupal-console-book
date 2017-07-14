# database:log:poll
वॉचडॉगला मत द्या आणि नवीन लॉग नोंदी प्रत्येक x सेकंद प्रिंट करा

**Usage:**
```
drupal database:log:poll [arguments] [options]
dblp
```

## Available options
Option | Details
-------|-------------
--type | विशिष्ट प्रकाराद्वारे इव्हेंट फिल्टर करा.
--severity | एका विशिष्ट स्तर तीव्रतेने इव्हेंट फिल्टर करा.
--user-id | विशिष्ट वापरकर्ता आयडी द्वारे इव्हेंट फिल्टर करा.

## Available arguments
Argument | Details
---------|-------------
duration | सेकंदात जेथून डेटाबेस वाचणे दरम्यान झोपण्याची कालावधी.

## Examples
* प्रत्येक x सेकंद स्क्रीनवर लॉग प्रविष्टी मुद्रित करा
```
drupal database:log:poll \
  100
```
