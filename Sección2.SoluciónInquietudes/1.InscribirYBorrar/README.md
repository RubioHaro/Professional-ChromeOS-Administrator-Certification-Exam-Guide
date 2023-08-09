# 1. Borrar datos de dispositivos ChromeOS  
Es posible borrar los datos de usuario y del dispositivo local buscando solucionar problemas o eliminar datos por otros motivos. Si el dispositivo está registrado en una organización, es posible hacer el borrado sus datos de forma remota. Si está registrado en una organización, se pueden borrar manualmente los datos locales. Para obtener más información, consulta la sección [Borrar manualmente los datos de un dispositivo ChromeOS](https://support.google.com/chrome/a/answer/1360642?hl=es&ref_topic=6274426&sjid=15639427309961008952-NA#manual_wipe).

**Nota:** Para gestionar un dispositivo ChromeOS de tu organización, este debe [registrarse](https://support.google.com/chrome/a/answer/1360534) antes de que _**cualquier**_ usuario inicie sesión en él (incluido tú como administrador). Si un usuario inicia sesión antes de que se registre el dispositivo, no se aplicarán las políticas ni las preferencias de tu cuenta de Google Workspace. Además, deben borrarse los datos del dispositivo para reiniciar el registro y gestionar el dispositivo en tu organización.
## Borrar los datos de un dispositivo ChromeOS de forma remota
Solo los administradores pueden borrar de forma remota los datos de los dispositivos, que deben estar gestionados. Este proceso solo restablece el dispositivo. Para dar de baja y restablecer un dispositivo de forma remota, consultar el artículo [Reparar, reaprovechar o retirar dispositivos ChromeOS](https://support.google.com/chrome/a/answer/3523633).

## Inhabilitar Dispositivos

Es posible Inhabilitar un dispositivo si este es perdido o robado. Los dispositivos inhabilitados permanecen registrados el dominio al que este este asociado.

Dependiendo de la licencia asociada al dispositivo, es posible utilizarla para registrar otro dispositivo en el mismo dominio o para volver a registrar un dispositivo Chromebook Enterprise en otro dominio. Para obtener más información sobre las licencias, consultar el artículo [Opciones para hacer pedidos de Chrome Enterprise](https://support.google.com/chrome/a/answer/9147838).

**Importante:** Es posible que los dispositivos de tu organización no se inhabiliten correctamente a menos que esté activada la opción que obliga a volver a registrarlos.

## Estados de los Dispositivos

| Estado          | Se muestran dispositivos                                    | Acciones que puedes realizar directamente en esta vista                                              |
|-----------------|------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| Aprovisionado   | Registrados correctamente                                  | Dar de baja o inhabilitar (siguiendo los pasos que se describen más arriba).                       |
| Preaprovisionado| Preparados para la activación automática en cuanto se conecten a una red | Eliminar o inhabilitar (consulta los pasos detallados arriba).                                   |
| Dado de baja    | Dados de baja                                               | Ninguna acción directa. Consulta los pasos descritos más arriba para borrar los datos del dispositivo y volver a registrarlo. |
| Inhabilitado    | Inhabilitados                                               | Volver a habilitar o dar de baja (siguiendo los pasos que se describen más arriba).               |
| Suspendido      | Registrados correctamente, pero sus suscripciones han caducado | Dar de baja.                                                                                        |
| Todos           | Registrados, dados de baja o inhabilitados correctamente | Ninguna acción directa.                                                                             |

Si inhabilitas accidentalmente un dispositivo o si aparece uno que se había extraviado, puedes **volver a habilitarlo**. Antes de volver a habilitar el dispositivo, asegúrate de que tienes una licencia disponible.

*Nota:** Cuando des de baja o inhabilites un dispositivo, deberás conectarlo a Internet para aplicar los cambios. Este paso es necesario para permitir que el dispositivo ChromeOS comunique su estado al servidor.*

Documentación: https://support.google.com/chrome/a/answer/3523633?hl=es&ref_topic=6274426&sjid=7525377380221841232-NA#zippy=%2Cdar-de-baja-un-dispositivo%2Cinhabilitar-un-dispositivo%2Cvolver-a-habilitar-un-dispositivo 


