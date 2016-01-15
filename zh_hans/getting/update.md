# 如何更新
Drupal 8 处于 heavy 开发状态，要使 Drupal Console 与 Drupal 8 的最新更新保持同步，更新Drupal Console的方式， 使用自动更新命令是最简单的，也是推荐的方式。

## 取决于安装时使用的方法

### 全局安装（并重命名为'drupal'）
```
$ drupal self-update
```

### 全局安装 （使用的是 composer）
```
$ composer global update drupal/console:@stable
```

### 本地安装 (下载的 console.phar 文件)
在 console.phar 文件所在目录运行
```
$ php console.phar self-update
```

