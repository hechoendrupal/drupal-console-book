# user:create
अनुप्रयोगासाठी वापरकर्ते तयार करा.

**वापर:**
```
drupal user:create [arguments] [options]
uc
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--roles | वापरकर्ता भूमिका.
--email | वापरकर्ता ईमेल.
--status | वापरकर्ता स्थिती.

## उपलब्ध वितर्क
वितर्क | तपशील
---------|-------------
username | वापरकर्ता नाव तयार करणे.
password | वापरकर्ता संकेतशब्द.

## उदाहरणे
* वापरकर्तानाव, संकेतशब्द, भूमिका, ईमेल आणि स्थिती निर्दिष्ट करणारे वापरकर्ता तयार करा.
```
drupal user:create  john p455w0rd  \
  --roles='authenticated'  \
  --email="john@anexusit.com"  \
  --status="1"
```
* वापरकर्तानाव, संकेतशब्द, भूमिका, ईमेल आणि स्थिती निर्दिष्ट करणारा प्रशासक वापरकर्ता तयार करा.
```
drupal user:create  doe p455w0rd  \
  --roles='administrator'  \
  --email="doe@anexusit.com"  \
  --status="1"
```
