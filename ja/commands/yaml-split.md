# yaml:split
インデントを区切り基準に指定してYAMLファイル分割する

**使い方:**
```
$ drupal yaml:split [arguments] [options]
$ ys  
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--indent-level | 特定のインデントレベルを使ってYAMLファイルを分割する
--file-output-prefix | commands.yaml.split.options.file-output-prefix
--file-output-suffix | commands.yaml.split.options.file-output-suffix
--starting-key | 要素を部分的に抽出するために有用な、分割の開始位置を示すYAMLキー
--exclude-parents-key | 生成されたファイルで親キーを除外する

## 利用可能な引数
引数 | 詳細
---------|-------------
yaml-file | commands.yaml.split.value.arguments.yaml-file
