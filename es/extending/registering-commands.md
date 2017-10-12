# Registrando comandos

Para hacer los comandos de consola disponibles dentro de una instalación Drupal necesitará registrar su clase Command como servicio usando el archivo `console.services.yml` en el raíz de su extensión (módulo, theme, profile) y etiquetar la definición del servicio como `drupal.command`.
```
services:
  example.example_default:
    class: Drupal\example\Command\DefaultCommand`
    arguments: ['@entity_type.manager']
    tags:
      - { name: drupal.command }
```
> NOTA: La sección `arguments` en la definición del servicio es opcional y sólo se usa si va a inyectar servicios en su comando desde el contenedor de servicios.
