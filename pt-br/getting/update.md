# Atualizar projeto
O Drupal 8 está em desenvolvimento intenso, para manter a sincronia com as últimas mudanças. A maneira mais fácil e recomendável de atualizar o Drupal Console é usando o comando de atualização automática.

## Dependendo do método de instalação:

### Instalado globalmente (e renomeado para "drupal"):
```
$ drupal self-update
```

### Instalado globalmente (usando composer):
```
$ composer global update drupal/console:@stable
```

### Instalado localmente (executando a partir do diretório onde o console.phar foi baixado):
```
$ php console.phar self-update
```

