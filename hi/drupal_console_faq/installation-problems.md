# स्थापना की समस्याओं

जब आप अपने Drupal 8 रूट निर्देशिका से DrupalConsole चलाने, आप विभिन्न त्रुटि संदेश प्राप्त कर सकते हैं, हम रिपोर्ट की समस्याओं को संकलित करने की कोशिश करेंगे और उन्हें कैसे तय करना है|

---

त्रुटि संदेश:
```
[PDOException] SQLSTATE[HY000] [2002] No such file or directory
```
आप को संपादित करने की आवश्यकता होगी अपने 'host' में 'settings.php' फ़ाइल|

`sites/default/settings.php` पर जाए| `settings.php` फ़ाइल में, बदलाव `host` पढ़ने के लिए:
```
'host' => '127.0.0.1'
```
या तो अपने 'settings.php' फ़ाइल पहले से ही पढ़ता:
```
'host' => '127.0.0.1'
```
पढ़ने के लिए इसे बदल:
```
'host' => 'localhost'.
```
आप परिवर्तन करने के बाद, फाइल को सुरक्षित के लिए सुनिश्चित करें और उसके बाद फिर से DrupalConsole चलायें|

---

त्रुटि संदेश:
```
[PDOException]
SQLSTATE[HY000] [2002] Can't connect to local MySQL server through socket '/tmp/mysql.sock'
```
Creating a symlink pointing to `/tmp/mysql.sock`:
```
ln -s /path/to/your/mysql/data/mysql.sock /tmp/mysql.sock
```

