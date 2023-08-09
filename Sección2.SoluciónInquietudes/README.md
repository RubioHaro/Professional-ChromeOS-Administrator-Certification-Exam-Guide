# Sección 2. Solución de Problemas a Inquietudes de los Clientes

![[Professional-ChromeOS-Administrator-Certification-Exam-Guide/Sección2.SoluciónInquietudes/imagen1.png]]
## Índice de la Sección

1. Borrar dispositivos 
2. Obtener registros de dispositivos (desde el dispositivo) 
3. Registrar tickets de soporte
4. Resolver problemas de conectividad 
5. Ayudar al inicio de sesión de los usuarios por primera vez 
6. Comprobar los dispositivos manualmente para las actualizaciones 
7. Enviar solicitudes de características
8. Estar al tanto del Programa de Probadores de Confianza
9. Informar a los socios de las notas de la versión

## Inquietudes de los Clientes

Google Chrome OS a comenzado a implementarse por diferentes organizaciones debido a las diversas ventajas cómo la seguridad y el rendimiento. Sin embargo, debido a que ChromeOS es un sistema operativo relativamente nuevo, es natural enfrentarse a diversas inquietudes relacionadas con temas de funcionalidad, seguridad entre otras. Esta sección busca resolver dichas inquietudes. Así cómo dar una guía de cuando conviene o no utilizar ChromeOS comenzando con algunos de los mitos de ChromeOS:

* ChromeOS requiere de internet para funcionar. 
* ChromeOS requiere licencias de Google.
* ChromeOS es solo para equipos antiguos o legados.

## Operando en la Consola de Administración: Solución de Problemas de las Inquietudes de los Clientes

### 1. Borrar Dispositivos
Inscribe los dispositivos Chrome que deseas gestionar desde tu Consola de administración. Borra o desprovee los dispositivos perdidos o robados.

Seguir en 1.Inscribir y Borrar 
### 2. Obtener registros de dispositivos (desde el dispositivo) 
Al momento de encontrar errores o funciones que no brindan los resultados esperados, es necesario leer la documentación y en caso de confirmar que algún componente o función no funciona correctamente es importante, antes de contactar el soporte técnico, contar con los registros del dispositivo: 

Los registros de tu dispositivo Chrome pueden ser analizados con Log Analyzer (https://toolbox.googleapps.com/apps/loganalyzer/) para intentar identificar el problema que se está experimentando. Si aún así no es posible resolver el problema, tener los registros a la mano cuando se haga contacto con el equipo de Asistencia facilitará la resolución del problema.

Antes de ponerte en contacto con el equipo de Asistencia, te recomendamos que obtengas los registros (o logs) de tu dispositivo Chrome gestionado y los analices con Log Analyzer para intentar identificar el problema que estás experimentando. Si no consigues resolver el problema, ten los registros a mano cuando te pongas en contacto con el equipo de Asistencia.

Los logs pueden ser consultados desde el navegador, estos se encuentran en la ruta de sistema: /var/log, y podemos acceder a ellos desde el navegador escribiendo file:///var/log en la barra de direcciones.

![[Professional-ChromeOS-Administrator-Certification-Exam-Guide/Sección2.SoluciónInquietudes/imagen2.png]]
Ejemplo de Logs mostrados desde el navegador. 

Podemos descargar estos logs, o visualizarlos directamente haciendo click en el log deseado.

![[Professional-ChromeOS-Administrator-Certification-Exam-Guide/Sección2.SoluciónInquietudes/imagen3.png]]
Ejemplo de log de bluetooth.

Documentación sobre logs: https://support.google.com/chrome/a/answer/6270826?hl=en#zippy=%2Ccollect-network-logs%2Cread-the-logs-manually




Referencias: 
* https://workspace.google.com/intl/es-419_mx/products/admin/
* https://cloud.google.com/identity?hl=es-419

