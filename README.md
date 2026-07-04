# Bot RPA para Consulta Automatizada de RUC en SUNAT con Power Automate Desktop

## Flujo RPA

En muchas actividades administrativas es necesario validar información tributaria de empresas, proveedores o clientes mediante la consulta de RUC en el portal de SUNAT. Cuando este proceso se realiza de forma manual, el usuario debe ingresar cada RUC uno por uno, esperar la respuesta de la página, copiar los datos relevantes, registrar el resultado y guardar alguna evidencia de la consulta.

Este tipo de tarea es repetitiva, consume tiempo y puede generar errores humanos, especialmente cuando se trabaja con varios registros. Por ello, se desarrolló este proyecto RPA con Power Automate Desktop, con el objetivo de automatizar la consulta de RUC, extraer información importante del contribuyente y generar reportes documentales de forma ordenada.

El bot permite leer una lista de RUC desde un archivo Excel, consultar cada registro en SUNAT, generar una ficha PDF por cada RUC válido, actualizar el estado del proceso en el mismo Excel, registrar logs de ejecución, comprimir los reportes generados y preparar el envío de resultados por correo electrónico.
