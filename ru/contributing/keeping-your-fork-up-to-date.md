# Поддержание актуальности fork

Через некоторое время ваш репозиторий (forked) и оригинальный (называемый upstream) будут рассинхронизированы, оставляя вас со старой, неподдерживаемой версией.

Для синхронизации изменений, которые вы сделали в вашей fork с оригинальным репозиторием, вам следует:

## Сконфигурировать удаленную fork:
Определите и сконфигурируйте новый удаленный upstream репозиторий, который указывает на upstream репозиторий расположенный в Git.
```
git remote add upstream https://github.com/hechoendrupal/drupal-console.git
```
Для более подробной информации посетите GitHub руководство [Конфигурация удаленной fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)

## Синхронизация вашей fork
Синхронизация вашей fork для поддержки актуальной версии с upstream репозиторием.
```
git fetch upstream
git merge upstream/master
```
Для более подробной информации посетите GitHub руководство [Синхронизация fork](https://help.github.com/articles/syncing-a-fork/)
