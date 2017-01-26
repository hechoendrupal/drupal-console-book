# 保持更新

过段时间，你 forked 的 repository 和原始的 repository (叫 upstream) 会不一致。

你 forked 的 repository 和原始的 repository 要想保持一致，你需要：

## 配置 remote fork:
指定并配置一个新的 remote upstream repository 指向 upstream repository
```
git remote add upstream https://github.com/hechoendrupal/drupal-console.git
```
更多细节，请访问 Github 提供的文档[Configuring a remote fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)  

## 同步你的 fork
同步你的 fork 与 upstream repository 保持一致
```
git fetch upstream
git merge upstream/master
```
更多细节，请访问 Github 提供的文档 [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
