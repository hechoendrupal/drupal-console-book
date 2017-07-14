# create:vocabularies
ダミーのボキャブラリーを追加

**application.gitbook.messages.usage:**
```
drupal create:vocabularies [options]
crv
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--limit | 作成するボキャブラリーの数
--name-words | ボキャブラリーの名前に設定するの単語の最大数

## application.gitbook.messages.examples
* Provide the number of vocabularies to create and maximum number of words in vocabulary names
```
drupal create:vocabularies \
  --limit="5" \
  --name-words="5"
```
