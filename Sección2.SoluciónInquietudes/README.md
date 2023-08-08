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

## Solución de Problemas de las Inquietudes de los Clientes

La Consola de administración de Google es una plataforma web donde los administradores de un dominio gestionan los servicios de Google para las personas en una organización. 

La Consola de administración se encuentra disponible desde: https://admin.google.com/

Algunas de sus funciones son: agregar o eliminar usuarios de una organización, administrar la facturación, configurar dispositivos móviles, por mencionar algunas. 

## ¿Cómo se Obtiene Acceso a la Consola?

### Las Organizaciones

El recurso de **organización** en Google representa a una organización del mundo real (por ejemplo, una empresa) y es el nodo raíz en la jerarquía de recursos de Google Cloud. Las organizaciones están sujetas a un dominio, por ejemplo: *empresa.com*.

El recurso de organización es el recurso principal de las carpetas y los recursos de proyectos. Las políticas de control de acceso de IAM aplicadas en el recurso de organización se aplican en la jerarquía de todos los recursos de la organización.

El recurso de organización está estrechamente asociado con una cuenta de Google Workspace o Cloud Identity. Una creada una cuenta de Google Workspace o Cloud Identity, en el momento que se realice la asociación con un dominio, el recurso de organización se creará automáticamente.

Los enlaces para la creación de organización con cuenta Workspace, Cloud Identity, son diferentes entre sí además de requerir un proceso adicional al ser creado con algún partner de Google.

## Usuarios e Identidad

La consola de administración de Google permite la administración los usuarios que pertenezca a una organización así como la configuración de identidad. Es posible que los usuarios sean sincronizados desde servidores on-premise o con directorios activos de servicios de terceros (como Azure Directory). 

Además para cada usuario podemos asignarle algún tipo de cuenta según el licenciamiento que se necesite*: 
* Cloud Identity: Cuentas gratuitas limitadas a servicios básicos de Google (sin correo ni ofimática)
* Cuentas Google Workspace (Con correo electrónico y servicios de Ofimática de Google como Google Docs, Google Meets, entre otros)

*Revisar licenciamiento de Cuentas de Google: Cloud Identity y Google Workspace.* *

## Interfaz de la consola

La consola de administración nos muestra un dashboard donde podemos ver un resumen de los usuarios que se tienen, así como accesos rápidos a creación de usuarios, eliminación y actualización de usuarios. Así como los dominios registrados, administrar facturación y métodos de pago. Y, finalmente, novedades y actualizaciones.

![[imagen2.png]]

En el menú lateral izquierdo, encontramos las diversas opciones mencionadas, el acceso al dashboard, la sección de administración de usuarios, y la sección de dispositivos que será de especial interés para la certificación de ChromeOS Administrator. 

![[imagen3.png]]
Existen diversos recursos para aprender más sobre la consola de administración:

En Coursera tenemos Introducción a Cloud Identity: https://www.coursera.org/learn/cloud-identity
e Introducción a Administración de Google Workspace https://www.coursera.org/learn/introduction-google-workspace

Así como la documentación oficial: 
* Cloud Identity: https://cloud.google.com/identity
* Google Workspace: https://workspace.google.com/

Referencias: 
* https://workspace.google.com/intl/es-419_mx/products/admin/
* https://cloud.google.com/identity?hl=es-419

