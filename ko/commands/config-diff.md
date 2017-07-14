# config:diff
디렉토리와 비교한 활성 설정과 다른 설정 항목들을 출력합니다.

**application.gitbook.messages.usage:**
```
drupal config:diff [arguments] [options]
cdi
```

## application.gitbook.messages.options
application.gitbook.messages.option | application.gitbook.messages.details
-------|-------------
--reverse | 차이점을 거꾸로 봅니다. (예를 들어 활성 설정를 기준으로 디렉토리와의 차이점 조회)

## application.gitbook.messages.arguments
application.gitbook.messages.argument | application.gitbook.messages.details
---------|-------------
directory | 차이점을 조회하려는 디렉토리. 생략하면 드루팔 설정 디렉토리로 합니다.

## application.gitbook.messages.examples
* Provide a config directory
```
drupal config:diff ../config/path
```
