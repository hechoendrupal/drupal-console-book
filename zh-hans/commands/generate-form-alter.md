# generate:form:alter
生成 hook_form_alter() 或 hook_form_FORM_ID_alter 实现

**使用方法:**
```
drupal generate:form:alter [options]
gfa
```

## 可用选项
选项 | 详细信息
-------|-------------
--module | 模块名
--form-id | 要修改（Alter）的的表单(Form)ID
--inputs | 在表单中创建输入。

## 例子
* Generate a hook form alter for an empty form specifying the module name
```
drupal generate:form:alter  \
  --module="modulename"
```
* Generate a hook form alter with 2 fields specifying the module name and the inputs
```
drupal generate:form:alter  \
  --module="modulename"  \
  --inputs='"name":"inputtext", "type":"text_format", "label":"InputText", "options":"", "description":"Just an input text", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'  \
  --inputs='"name":"email", "type":"email", "label":"Email", "options":"", "description":"Just an email input", "maxlength":"", "size":"", "default_value":"", "weight":"0", "fieldset":""'
```
