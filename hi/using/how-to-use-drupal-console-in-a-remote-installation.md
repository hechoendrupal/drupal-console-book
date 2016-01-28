# एक दूरस्थ साइट स्थापना में Drupal कंसोल का उपयोग कैसे करें

Drupal कंसोल आप अपने स्थानीय सर्वर पर कमांडों को चलाने, लेकिन वास्तव में एक रिमोट सर्वर पर उन पर उनको चलाने की अनुमति देता है|

आप इस सुविधा का लाभ ले सकते हैं, `--target` विकल्प का उपयोग करते हुए और सर्वाधिक दूरस्थ साइट नाम आप जिस के साथ वार्तालाप करना चाहते हैं|
```
$ drupal --target=sample.dev cr all
```

एक दूरस्थ साइट का उपयोग करने के लिए अपने स्थानीय कंप्यूटर की स्थापना एक छोटी सी विन्यास की आवश्यकता है|

### वैश्विक विन्यास संपादित करें
आप दूरस्थ कनेक्शन के लिए वैश्विक विन्यास प्रदान कर सकते हैं `~/.console/config.yml` नकल की फ़ाइल पर| उसकी जानकारी के भीतर बांटा है `remote` कुंजी.
```
application:
  ...
  remote:
    user: root
    port: 22
    console: /usr/local/bin/drupal
    options:
    arguments:
    keys:
      public: ~/.ssh/id_rsa.pub
      private: ~/.ssh/id_rsa
      passphrase: ~/.ssh/passphrase.txt
```

### विशिष्ट साइट विन्यास संपादित करें
आप विशिष्ट साइट विन्यास प्रदान कर सकते हैं डुप्लिकेटिंग नकल साइट फ़ाइल द्वारा `~/.console/sites/sample.yml` पर एक नया नाम के साथ `~/.console/sites/`.

```
local:
  root: /var/www/drupal8.dev
  host: local
dev:
  root: /var/www/html/drupal
  host: 140.211.10.62
  user: drupal
prod:
  root: /var/www/html/docroot
  host: live.drupal.org
  user: drupal
  console: /var/www/html/docroot/console.phar
```

### डीबग साइटों.
आप सबी ज्ञात स्थानीय और दूरस्थ साइटों को सूचीबद्ध कर सकते इस कमांड को चला कर `site:debug` कमांड|
```
$ drupal site:debug

+--------------------+-----------------+------------------------+
| Site               | Host            | Root                   |
+--------------------+-----------------+------------------------+
| sample.local       | local           | /var/www/drupal8.dev   |
| sample.dev         | 140.211.10.62   | /var/www/html/drupal   |
| sample.prod        | live.drupal.org | /var/www/html/docroot  |
+--------------------+-----------------+------------------------+
```

आप तर्क के रूप में साइट के नाम से सर्वाधिक साइट विन्यास विवरण दिखा सकते हैं `site:debug` कमांड को|
```
$ drupal site:debug sample.dev

user: drupal
port: 22
console: /usr/local/bin/drupal
options:
arguments:
keys:
    public: ~/.ssh/id_rsa.pub
    private: ~/.ssh/id_rsa
    passphrase: ~/.ssh/passphrase.txt
root: /var/www/html/drupal
host: 140.211.10.62
remote: true
```

**NOTE:** आप नोटिस कर सकते हैं जब एक साइट डिबगिंग होती है तब वैश्विक विन्यास और विशिष्ट साइट विन्यास विलय हो जाते हैं| आप साइट विशिष्ट विन्यास पर उन कुंजी जोड़कर किसी भी वैश्विक विन्यास ओवरराइड कर सकते हैं|
