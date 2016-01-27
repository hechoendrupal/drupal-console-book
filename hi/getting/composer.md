# Composer का उपयोग करके Drupal कंसोल स्थापित करें
Composer का उपयोग करके आप इस परियोजना को स्थापित कर सकते हैं|

## Composer का उपयोग करके Drupal कंसोल सार्वभौमिक रूप से स्थापित करें:
```
$ composer global require drupal/console:@stable
```

## दोहरी निर्देशिका को अपने क्लास पथ से जोड़ें:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## इसको प्रयोग करके अब आप कंसोल को निष्पादित कर सकते:
```
$ drupal generate:module
```
