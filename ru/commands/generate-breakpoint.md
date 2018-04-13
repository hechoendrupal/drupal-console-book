# generate:breakpoint
Генерирует брейкпоинт

**Использование:**
```
drupal generate:breakpoint [options]
gb
```

## Доступные параметры
Команда | Детали
-------|-------------
--theme | Имя темы
--breakpoints | Брейкпоинты

## Примеры
* Генерирует брейкпоинт по имени темы, имени брейкпоинта, заголовку, медиа запросу, весу и умножителю
```
drupal generate:breakpoint  \
  --theme="classy"  \
  --breakpoints='"breakpoint_name":"narrow", "breakpoint_label":"narrow", "breakpoint_media_query":"all and (min-width: 560px) and (max-width: 850px)", "breakpoint_weight":"1", "breakpoint_multipliers":"1x"'
```
