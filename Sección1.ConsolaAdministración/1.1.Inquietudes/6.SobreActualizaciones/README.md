# Sección 1.6 Sobre las Actualizaciones

De forma predeterminada, los dispositivos ChromeOS se actualizan en cuanto se lanza la versión más reciente del sistema operativo. Te recomendamos que no cambies este ajuste. De este modo, las versiones nuevas de ChromeOS se instalarán automáticamente en los dispositivos de tus usuarios en cuanto se lancen en el canal estable, y tus usuarios recibirán las correcciones de errores de seguridad más importantes y las nuevas funciones en cuanto estén disponibles.

## Desactivar las actualizaciones automáticas

Si una determinada versión de ChromeOS causa algún problema en tu organización, puedes desactivar las actualizaciones automáticas hasta que se resuelva. Tus usuarios ya no podrán comprobar manualmente si hay actualizaciones. Para ello, sigue estos pasos:

1. En la consola de administración, busca Dispositivos -> Chrome -> Configuración -> Configuración de dispositivos.
2. Ve a Configuración de actualización de dispositivos.
3. Haz clic en Configuración de actualizaciones automáticas.
4. Selecciona Bloquear actualizaciones.
5. Haz clic en Guardar.

## Redes con ancho de banda limitado

Si tu organización tiene una red con ancho de banda limitado, es posible configurar las actualizaciones de forma escalonada para que no se sature la red. O bien, utilizar la actualizaciones de punto a punto (P2P), es decir, los dispositivos pueden recibir actualizaciones de otros dispositivos (DEL MISMO MODELO) que se encuentren en la misma red, reduciendo así el tráfico de red externo. Es posible que esta función (P2P) no esté disponible dependiendo la configuración de red de tu organización.

### Actualizaciones escalonadas

Con esta opción, puedes repartir las actualizaciones en varios días. Sin embargo, te recomendamos que selecciones el periodo más corto posible (por ejemplo, dos o tres días). Si decides distribuirlas en un periodo más largo, es posible que los dispositivos de algunos usuarios vayan varias versiones por detrás respecto a la más reciente.

Las descargas se producen en horarios diferentes durante este periodo para evitar que se produzcan picos de tráfico que puedan afectar a redes antiguas o con un ancho de banda bajo. Los dispositivos que estén sin conexión durante este periodo descargarán la actualización en cuanto vuelvan a conectarse. Para configurar las actualizaciones escalonadas, sigue estos pasos:

1. En la consola de administración, busca Dispositivos -> Chrome -> Configuración -> Configuración de dispositivos.
2. Ve a Configuración de actualización de dispositivos.
3. Haz clic en Configuración de actualizaciones automáticas.
4. En Plan de implementación, selecciona Distribuir actualizaciones.
5. En Distribuir aleatoriamente las actualizaciones en, selecciona el periodo de tiempo que prefieras (dos o tres días).
6. Haz clic en Guardar.

### Actualizaciones de punto a punto (P2P)

Si hay una red de punto a punto (P2P) disponible, los dispositivos Chrome pueden recibir actualizaciones automáticamente de otros dispositivos del mismo modelo que se encuentren cerca.  Si este tipo de actualización no funciona o no puede utilizarse en tu red, los dispositivos se actualizarán de la forma habitual: descargarán la actualización de los servidores de Google o de un servidor proxy web intermedio con función de almacenamiento en caché.

Para que las actualizaciones automáticas P2P funcionen, se deben cumplir estos requisitos:

1. La red de tu organización debe permitir las conexiones P2P.
2. No debe excluirse ni bloquearse el DNS multidifusión (mDNS) en la red de área local (LAN).



## Canales de actualización

ChromeOS tiene cinco canales de actualización: Asistencia a largo plazo (LTS), Candidato a asistencia a largo plazo (LTC), Estable, Beta y Dev (o desarrolladores). Cada canal tiene un nivel de estabilidad y frecuencia de actualización diferente.

Si eliges el canal de lanzamiento Candidato a asistencia a largo plazo (LTC) o Asistencia a largo plazo (LTS), los dispositivos recibirán actualizaciones de funciones acumulativas cada seis versiones (aproximadamente cada seis meses). Los dispositivos que estén en los canales LTC o LTS seguirán recibiendo correcciones de seguridad cada dos semanas.

Para proteger los dispositivos ChromeOS y mantenerlos actualizados, te recomendamos que utilices las actualizaciones automáticas. Si tu organización tiene miles de dispositivos o si el ancho de banda de tu red es insuficiente, quizá tengas que personalizar el modo en que se implementan las actualizaciones.

Recomendación: Mantén a la mayoría de los usuarios en el canal estable o LTS. ¿Porqué?, El equipo de pruebas de ChromeOS prueba todas las funciones del canal estable. Es el canal que deberían utilizar la mayoría de tus usuarios. Se actualiza cada dos o tres semanas en el caso de versiones secundarias y cada cuatro semanas para las versiones principales.

## Personalizar las actualizaciones

Google ChromeOs permite personalizar las actualizaciones de los dispositivos con las siguientes opciones:

* **Fijar las Actualizaciones de ChromeOS a una versión (NO RECOMENDADO)**: Si una determinada versión de ChromeOS causa algún problema en tu organización, puedes desactivar las actualizaciones automáticas hasta que se resuelva. Tus usuarios ya no podrán comprobar manualmente si hay actualizaciones.

* **Implementar las actualizaciones de forma progresiva (NO RECOMENDADO)**: Puedes enviar actualizaciones de ChromeOS a los dispositivos mediante un lanzamiento progresivo. Con este tipo de lanzamiento, solo un porcentaje de los dispositivos recibe inicialmente la actualización. Puedes aumentar este porcentaje posteriormente para implementar progresivamente las actualizaciones en todos los dispositivos de tu organización. También puedes configurar actualizaciones progresivas en grupos o departamentos específicos. Los dispositivos que indiques se elegirán de forma aleatoria cada vez que haya una nueva implementación.

* **Indicar a los usuarios que reinicien los dispositivos**: Puedes definir el periodo de las notificaciones en las que se indica a los usuarios que deben reiniciar sus dispositivos ChromeOS para aplicar las actualizaciones pendientes. Puedes hacer que los dispositivos se reinicien automáticamente cuando transcurra el tiempo especificado.

* **Acelerar las actualizaciones (RECOMENDADA PARA TODAS LAS ORGANIZACIONES)**: Cuando se instala una actualización en dispositivos ChromeOS, los usuarios deben reiniciarlos para que se aplique. Aunque reciben una notificación en la que se les pide que reinicien el dispositivo, es posible que no lo hagan inmediatamente.
    
    Si quieres que los dispositivos se reinicien lo antes posible, puedes hacer que se cierre la sesión de los usuarios cuando cierren la tapa. De este modo, si un usuario no reinicia su dispositivo después de actualizarlo, pero cierra la tapa, el dispositivo se reiniciará y se completará la actualización.

    **Nota Importante: No olvides avisar a los usuarios de que deben guardar su trabajo antes de cerrar la tapa para no perderlo.**

* **Actualizar desde la Cache**: Si en la red de tu organización se ha configurado un servidor proxy-caché intermedio, podrás usarlo para almacenar en caché las actualizaciones de ChromeOS. Como estas actualizaciones se descargan de los servidores de Google a través de HTTP, se pueden almacenar en caché en la mayoría de los servidores proxy web con función de almacenamiento en caché. Los servidores proxy-caché reducen el ancho de banda utilizado y mejoran los tiempos de respuesta, ya que las páginas web que se solicitan frecuentemente se guardan en la memoria caché y se reutilizan.
    
    Consultar detalle en referencias.


## Restaurar una versión anterior de ChromeOS

Como administrador, puedes restaurar temporalmente una versión anterior de ChromeOS. Por ejemplo, es posible que tengas que restaurar una versión anterior de ChromeOS si las aplicaciones esenciales de tus usuarios no funcionan correctamente después de actualizar la versión.

Para que los usuarios estén protegidos con las últimas actualizaciones de seguridad, es recomendable que utilicen la versión más reciente de ChromeOS. Al utilizar versiones anteriores de ChromeOS, los usuarios quedarán expuestos a problemas de seguridad conocidos.

Consultar más en: https://support.google.com/chrome/a/answer/12569990?sjid=16592306799118246647-NC



Referencias:

* Prácticas recomendadas sobre la versión de ChromeOS: https://support.google.com/chrome/a/answer/6025002?sjid=16592306799118246647-NC