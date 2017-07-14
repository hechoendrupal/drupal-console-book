# site:import:local
匯入或設定本地現存的 Drupal 專案

**Usage:**
```
drupal site:import:local [arguments] [options]
sil
```

## Available options
Option | Details
-------|-------------
--environment | 要匯入的環境模式名稱

## Available arguments
Argument | Details
---------|-------------
name | 指派名稱給建立的網站設定
directory | 現存的 Drupal 根目錄

## Examples
* Import local drupal project specifying the site name and the path
```
drupal site:import:local  SiteName /private/var/www/vhost/anexusit/drupal8.dev/web
```
