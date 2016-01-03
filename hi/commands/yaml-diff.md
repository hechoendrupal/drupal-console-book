# yaml:diff
The **yaml:diff** command दो YAML फाइल का अंतर देखने के लिये उनकी तुलना करें

**प्रयोग:**
```
$ drupal yaml:diff [arguments] [options] 
$ yd  
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--stats | Print statistics about YAML files comparation
--negate | विधि अंतर या समान तुलना दर्ज करें, सम्भवत निधि TRUE/FALSE या 0/1
--limit | परिणामों कि संख्या सीमित करें
--offset | सीमा का प्रारंभिक बिंदु

## उपलब्ध तर्कों  
तर्क | विवरण
---------|-------------
yaml-left | YAML file used as base to compare
yaml-right | YAML file used to determine missing or differences with base YAML file
