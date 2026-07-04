## Contexto del proyecto

En muchas actividades administrativas es necesario validar información tributaria de empresas, proveedores o clientes mediante la consulta de RUC en el portal de SUNAT. Cuando este proceso se realiza de forma manual, el usuario debe ingresar cada RUC uno por uno, esperar la respuesta de la página, copiar los datos relevantes, registrar el resultado y guardar alguna evidencia de la consulta.

Este tipo de tarea es repetitiva, consume tiempo y puede generar errores humanos, especialmente cuando se trabaja con varios registros. Por ello, se desarrolló este proyecto RPA con Power Automate Desktop, con el objetivo de automatizar la consulta de RUC, extraer información importante del contribuyente y generar reportes documentales de forma ordenada.

El bot permite leer una lista de RUC desde un archivo Excel, consultar cada registro en SUNAT, generar una ficha PDF por cada RUC válido, actualizar el estado del proceso en el mismo Excel, registrar logs de ejecución, comprimir los reportes generados y preparar el envío de resultados por correo electrónico.

## Problema identificado

La consulta manual de RUC en SUNAT puede presentar los siguientes inconvenientes:

- Alto consumo de tiempo cuando se procesan varios RUC.
- Riesgo de errores al copiar información manualmente.
- Falta de trazabilidad sobre qué registros fueron procesados correctamente.
- Dificultad para organizar evidencias individuales de cada consulta.
- Necesidad de consolidar resultados en archivos ordenados para su revisión posterior.

## Solución propuesta

La solución desarrollada automatiza el proceso mediante un flujo RPA que integra Excel, navegador web, Word, generación de PDF, logs y compresión de archivos. El flujo permite transformar una tarea manual y repetitiva en un proceso asistido, controlado y trazable.

El archivo Excel funciona como entrada y también como mecanismo de seguimiento, ya que el bot actualiza las columnas `ESTADO` y `DETALLE` según el resultado de cada consulta. De esta manera, el usuario puede identificar rápidamente qué RUC fueron atendidos correctamente y cuáles presentaron errores.


## Valor del proyecto

Este proyecto demuestra la aplicación práctica de la automatización RPA en un proceso real de validación tributaria. Su valor principal está en reducir el trabajo manual, mejorar la organización de resultados y generar evidencia documental de las consultas realizadas.

Además, el flujo incorpora manejo básico de errores, generación de logs y notificación final, lo que permite tener mayor control sobre la ejecución del proceso.



# Bot RPA para Consulta Automatizada de RUC en SUNAT con Power Automate Desktop




