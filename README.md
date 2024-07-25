# API del Banco Central de la República Argentina (BCRA)

## Registro de la API

Para registrar una aplicación y obtener el token de acceso, visita el siguiente enlace:
[Registro de la API](https://estadisticasbcra.com/api/registracion)

## Documentación de la API

Consulta la documentación completa de la API en el siguiente enlace:
[Documentación de la API](https://estadisticasbcra.com/api/documentacion)

## Nota Importante

Al utilizar la librería `requests`, es necesario utilizar `Authorization: Bearer {TOKEN}` en lugar de `Authorization: BEARER {TOKEN}` como indica la documentación oficial. Esto se debe a la sensibilidad del header a mayúsculas y minúsculas en este contexto.

Asegúrate de reemplazar `{TOKEN}` con tu token de acceso real.










