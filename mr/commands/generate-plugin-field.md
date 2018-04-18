# generate:plugin:field
फील्ड प्रकार, विजेट आणि फॉर्मेटर प्लगइन उत्पन्न करा.

**वापर:**
```
drupal generate:plugin:field [options]
gpf
```

## उपलब्ध पर्याय
पर्याय | तपशील
-------|-------------
--module | मॉड्यूलचे नाव.
--type-class | फील्ड प्रकार प्लगइन वर्ग नाव.
--type-label | फील्ड प्रकार प्लगइन लेबल.
--type-plugin-id | फील्ड प्रकार प्लगइन आयडी.
--type-description | फील्ड प्रकार प्लगइन वर्णन.
--formatter-class | फील्ड फॉर्मेटर प्लगइन वर्ग नाव.
--formatter-label | फील्ड फॉर्मेटर प्लगइन लेबल.
--formatter-plugin-id | फील्ड फॉर्मेटर प्लगिन आयडी.
--widget-class | फील्ड फॉर्मेटर प्लगइन वर्ग नाव.
--widget-label | फील्ड विजेट प्लगइन लेबल.
--widget-plugin-id | फील्ड विजेट प्लगइन आयडी.
--field-type | फील्ड प्रकार फॉर्मेटर आणि विजेट प्लगइन सह वापरले जाऊ शकते.
--default-widget | फील्ड प्रकार प्लगइनचे डीफॉल्ट फील्ड विजेट.
--default-formatter | फील्ड प्रकार प्लगइनचे डीफॉल्ट फील्ड फॉर्मेटर.

## उदाहरणे
* मॉड्यूल नाव, प्रकार (वर्ग, लेबल, प्लगिन आयडी आणि वर्णन), फॉर्मेटर (वर्ग, लेबल, प्लगइन आयडी) आणि विजेट (वर्ग, लेबल आणि प्लगइन आयडी) निर्दिष्ट करणारा फील्ड प्रकार, विजेट आणि फॉर्मेटर प्लगइन उत्पन्न करा.
```
drupal generate:plugin:field  \
  --module="modulename"  \
  --type-class="ExampleFieldType"  \
  --type-label="Example field type"  \
  --type-plugin-id="example_field_type"  \
  --type-description="My Field Type"  \
  --formatter-class="ExampleFormatterType"  \
  --formatter-label="Example formatter type"  \
  --formatter-plugin-id="example_formatter_type"  \
  --widget-class="ExampleWidgetType"  \
  --widget-label="Example widget type"  \
  --widget-plugin-id="example_widget_type"  \
  --field-type="example_field_type"  \
  --default-widget="example_widget_type"  \
  --default-formatter="example_formatter_type"
```
