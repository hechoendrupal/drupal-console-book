# yaml:diff
The **yaml:diff** command दो YAML फाइल का अंतर देखने के लिये उनकी तुलना करें

**Usage:**
```
$ drupal yaml:diff [arguments] [options] 
$ yd  
```

## Available options
Option | Details
-------|-------------
--stats | Print statistics about YAML files comparation
--negate | विधि अंतर या समान तुलना दर्ज करें, सम्भवत निधि TRUE/FALSE या 0/1
--limit | परिणामों कि संख्या सीमित करें
--offset | सीमा का प्रारंभिक बिंदु

## Available arguments
Argument | Details
---------|-------------
yaml-left | YAML file used as base to compare
yaml-right | YAML file used to determine missing or differences with base YAML file
