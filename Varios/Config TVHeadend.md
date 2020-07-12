# <b>Configuración común de TVheadend </B>
- Reiniciar TVheadend y activar el grabber:
```
Configuración - Canal/EPG - Módulos para Obtención de Guía - Interno: XMLTV: tv_grab_EPG_dobleM
```
- Programar el cron de TVheadend para que se ejecute todos los días a las 8:15.
```
Configuración - Canal/EPG - Obtener Guía - Internal Grabber Settings - Cronología multi-línea:
```
```
# Se ejecuta todos los días a las 8:15
15 8 * * *
```
- Forzar una actualización de la guía de programación</i>
```
Pulsar el botón "Volver a ejecutar los capturadores de EPG internos"
```
- Configurar guía para Live Channels/TVHClient o para KODI</i>
```
Configuración - General - EPG_Settings - Idioma(s) por defecto:
```
```
Spanish - Guía con colores para KODI
English - Guía sin colores para Live Channels/TVHClient