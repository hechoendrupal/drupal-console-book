# Drupal 8 को कैसे डाउनलोड, स्थापित और उपयुक्त करें

Drupal 8 अपने स्थानीय मशीन में कोशिश करने के लिए सबसे आसान तरीका है `chain` कमाण्ड चलाना और विकल्प पारित करें `--file=~/.console/chain/quick-start.yml` जैसे निम्न उदाहरण पर दिखाया गया है|

```
$ drupal chain --file=~/.console/chain/quick-start.yml
```
> NOTE: `~/.console/chain/quick-start.yml` कॉपी करने के क्रम में पहले आपको `drupal init` अपने सिस्टम पर चलानी चाहिए|

 `chain` कमाण्ड आप को कमाण्ड चलाने की स्वचालित करने में मदद करता है, आपको बाहरी YAML फ़ाइल को परिभाषित करने की इजाजत देता है, जिस में परिभाषा का नाम, विकल्प और  कमांडों की तर्कों है और फाइल में परिभाषित क्रम पर आधारित सूची को चलाता है|

प्रदान की फाइल `~/.console/chain/quick-start.yml` की सामग्री:
```
commands:
  - command: site:new
    arguments:
      site-name: drupal8.dev
      version: 8.0.0
  - command: site:install
    options:
        root: /Users/jmolivas/develop/drupal/sites/drupal8.dev
        langcode: en
        db-type: sqlite
        db-file: sites/default/files/.ht.sqlite
        site-name: 'Drupal 8 Quick Start'
        site-mail: admin@example.com
        account-name: admin
        account-mail: admin@example.com
        account-pass: admin
        generate-inline: true
    arguments:
        profile: standard
  - command: server
```

पिछले विन्यास कई कमांडो को चलाएंगे, इस मामले में जो कमांडें SQLite को प्रयोग करके Drupal को डाउनलोड और स्थापित करती है, और अंत में PHP के निर्माण सर्वर को शुरू करता है, अब आप केवल अपने ब्राउज़र खोलने की जरूरत है और इसको 127.0.0.1:8088 पर पॉइंट करें|

आप डुप्लिकेट या प्रदान YAML फ़ाइल पर परिवर्तन कर सकते हैं, डाउनलोड मॉड्यूल में कमांड्स को जोड़ने के लिए `module:download`, install modules `module:install` , import configurations `config:import` और अपने डेटाबेस बहाल `database:restore` या DrupalConsole द्वारा प्रदान की गई किसी भी अन्य कमाण्ड या अपने स्वयं के मॉड्यूल के द्वारा एक कस्टम कमाण्ड|