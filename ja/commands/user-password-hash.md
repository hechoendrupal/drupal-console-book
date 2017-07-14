# user:password:hash
プレーンテキストのパスワードからハッシュ値を生成

**Usage:**
```
drupal user:password:hash [arguments]
uph
usph
```

## Available arguments
Argument | Details
---------|-------------
password | プレーンテキストのパスワード (複数指定する場合は空白区切り)

## Examples
* Get hash of the word "p455w0rd"
```
drupal user:password:hash  p455w0rd
```
