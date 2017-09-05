# How to use Drupal Console in a remote installation

Site aliases can be executed using the `--target` option and passing the site name you want to interact with.
  
```
drupal --target=sample.dev cr all
```

Site aliases can also be executed by using the legacy `@` identifier as:

```
drupal @sample.dev cr all
```  
