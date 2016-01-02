# config:export:view
The **config:export:view** command एक व्यू को YAML संरूप में निर्यात करें ताकि वो किसी दूसरे वेबसाइट में पुनर्प्रयोग किया जाये।

**Usage:**
```
$ drupal config:export:view [arguments] [options] 
$ cev  
```

## Available options
Option | Details
-------|-------------
--module | मोड्यूल का नाम।
--optional-config | व्यू को ऐच्छिक YAML व्यवस्था स्वरूप अपने मॉड्यूल में निर्यात करें
--include-module-dependencies | व्यू मॉड्यूल निर्भरता को मॉड्यूल info YAML फाइल में सम्मिलित करें

## Available arguments
Argument | Details
---------|-------------
view-id | व्यू क्रमांक
