# generate:theme
Генерирует тему.

**Использование:**
```
drupal generate:theme [options]
gt
```

## Доступные параметры
Команда | Детали
-------|-------------
--theme | Название темы
--machine-name | Машинное имя (только буквы в нижнем регистре и знак подчеркивания)
--theme-path | Путь до темы
--description | Описание темы
--core | Версия ядра
--package | Пакет темы
--global-library | Имя глобальной библиотеки стилей
--libraries | Libraries
--base-theme | Базовая тема (например, classy, stable)
--regions | Регионы
--breakpoints | Контрольные точки

## Примеры
* Генерирует тему без регионов и контрольных точек по названию темы, машинному имени, пути темы, описанию, ядру Drupal, имени пакета и глобальной библиотеке
```
drupal generate:theme  \
  --theme="AnotherTheme"  \
  --machine-name="anothertheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="PackageName"  \
  --global-library="global-styling"  \
  --base-theme="false"
```
* Генерирует тему на основе темы stable с двумя регионами и одной контрольной точкой по названию темы, машинному имени, пути темы, описанию, ядру Drupal, имени пакета, глобальной библиотеке, базовой теме, регионам и контрольной точке
```
drupal generate:theme  \
  --theme="MyTheme"  \
  --machine-name="mytheme"  \
  --theme-path="/themes/custom"  \
  --description="My Awesome theme"  \
  --core="8.x"  \
  --package="MyThemePackage"  \
  --global-library="global-styling"  \
  --base-theme="stable"  \
  --regions='"region_name":"Content", "region_machine_name":"content"'  \
  --regions='"region_name":"Panel", "region_machine_name":"panel"'  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
