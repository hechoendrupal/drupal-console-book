# Ciclo de Vida de un Comando
 
Los comandos ejecutan tres métodos durante su ciclo de vida:

## El método `initialize` (inicializar) es optional.
Este método es ejecutado antes que los métodos `interact` y `execute`. 
Su propósito general es inicializar variables usadas en el resto de los métodos del comando.

## El método `interact` (interactuar) es optional.
Este método es ejecutado después de `initialize` y antes que `execute`.
Su propósito es verificar si algunas opciones o argumentos no se han establecido. En tal caso se pregunta interactivamente por dichos valores. Este es la última oportunidad para preguntar por opciones o argumentos no establecidos. Si al terminar de ejecutar este método no se han provisto todos los requerimientos se producirá un error.

## El método `execute` (ejecutar) es requerido.
Este método es ejecutado después de los métodos `initialize` e `interact`. 
Este contiene la lógica que quieres que el comando ejecute.
