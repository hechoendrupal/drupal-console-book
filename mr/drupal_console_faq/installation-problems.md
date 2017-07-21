# स्थापना समस्या 
जेव्हा आपण DrupalConsole आपल्या Drupal 8 रूट डाइरेक्टरीमधून चालवाल तेव्हा आपण वेगवेगळ्या त्रुटी संदेश मिळवू शकता, आम्ही रिपोर्ट केलेल्या समस्यांचे संकलन करण्याचा प्रयत्न करू आणि ते कसे निश्चित करायचे.

--- 

### त्रुटी संदेश:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
आपल्याला आपल्या 'settings.php' फाइलमध्ये आपले 'होस्ट' संपादित करणे आवश्यक आहे. 

`sites/default/settings.php` वर नेव्हिगेट करा. आपल्या `settings.php` फाईलमध्ये,`host` वाचण्यासाठी बदला:
```
'host' => '127.0.0.1'
```
किंवा आपल्या 'settings.php' फाईल आधीपासून वाचली असेल तर:
```
'host' => '127.0.0.1'
```
तो वाचण्यासाठी त्यास बदला:
```
'host' => 'localhost'. 
```
आपण बदल केल्यानंतर, फाईल सेव्ह करण्याची खात्री करा आणि नंतर पुन्हा DrupalConsole चालवा.

---

### त्रुटी संदेश:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
`/tmp/mysql.sock` वर इंगित करणारा सिमलिंक तयार करणे:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```

---

### त्रुटी संदेश:
```
Fatal error: require(): Failed opening required 'drupal.php'
```
हे ioncube लोडर विस्ताराद्वारे होऊ शकते, जे एन्कोड करण्यासाठी वापरले जाऊ शकते
आणि PHP फाइल्स डीकोड करा. हा विस्तार कोणत्याही phar फायलींना सामान्य कार्य करण्यास प्रतिबंधित करतो
आवश्यक असलेल्या कॉलसह / समाविष्ट करा आपण विस्तार अक्षम करणे आवश्यक आहे.

---

### त्रुटी संदेश:
```
The configuration date.timezone was missing and overwritten with America/Tijuana.
```
आपला टाइमझोन php.ini वर सेट नाही; आपणास आदेश पंक्तीसाठी योग्य php.ini संपादित करुन तो दुरुस्त करणे आवश्यक आहे (CLI साठी वेगळा php.ini आहे). 

`php --ini`चालवा आणि "लोड केलेली व्यूहरचना फाइल" पहा. उदाहरणार्थ, in Ubuntu: 
```
Loaded Configuration File:         /etc/php5/cli/php.ini
```
ती फाईल संपादित करा आणि शोधा
```
;date.timezone =
```
ही ओळ नक्कल करा आणि http://php.net/manual/en/timezones.php वर दिसत असलेल्या टाइमझोनला नियुक्त करा. 
