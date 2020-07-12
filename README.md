# EPG_dobleM
La guía de programación incluye:

* Cinco días de información de los canales de satelite y fibra de Movistar+
* Tres días de información del canal BOM Cine

El id de canales está sacado de la lista oficial de WEBGRAB, si ya tenías una guía cargada te tocará mapear algún canal

<p>
<a href="https://github.com/davidmuma/EPG_dobleM/blob/master/Varios/Canales%20soportados.md">Listado de canales soportados</a>
&nbsp&nbsp&nbsp&nbsp&nbsp
<a href="https://github.com/davidmuma/EPG_dobleM/blob/master/Varios/changelog.md">Changelog</a>
</p>

* 05/07/20: MODIFICADO EL GRABBER
* Ahora teneís dos guias, una con posters y otra con fanarts.
* Por defecto la guia es con posters, si la quereís con fanarts teneis que borrar el grabber antigüo, descargar el nuevo y modificar la linea enable_fanart=false por enable_fanart=true

## <b>Guía sin tags de colores</B>
- Enlace con la guía sin colores y con posters para aplicaciones tipo Tivimate
```
https://github.com/davidmuma/EPG_dobleM/blob/master/guiatv_sincolor.xml.gz?raw=true
```
- Enlace con la guía sin colores y con fanarts para aplicaciones tipo Tivimate
```
https://github.com/davidmuma/EPG_dobleM/blob/master/guiafanart_sincolor.xml.gz?raw=true
```

## <b>Instalar guía en LibreELEC / CoreELEC</B>
- Descargar el archivo <i>"tv_grab_EPG_dobleM"</i> en la siguiente ruta: 
```
wget -P /storage/.kodi/addons/service.tvheadend42/bin/ https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/tv_grab_EPG_dobleM
```
- Dar permisos de ejecución:
```
chmod 777 /storage/.kodi/addons/service.tvheadend42/bin/tv_grab_EPG_dobleM
```
- Ir al apartado <a href="https://github.com/davidmuma/EPG_dobleM/blob/master/Varios/Config%20TVHeadend.md">"Configuración común de TVheadend"</a>

## <b>Instalar guía en Linux / Synology </B>
- Descargar el archivo <i>"tv_grab_EPG_dobleM"</i> en /usr/local/bin:
```
sudo wget -P /usr/local/bin/ https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/tv_grab_EPG_dobleM
```
- Dar permisos de ejecución al grabber:
```
sudo chmod 777 /usr/local/bin/tv_grab_EPG_dobleM
```
- Ir al apartado <a href="https://github.com/davidmuma/EPG_dobleM/blob/master/Varios/Config%20TVHeadend.md">"Configuración común de TVheadend"</a>


## Imágenes
- KODI
![alt text](https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/Images/Kodi_1.jpg)
![alt text](https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/Images/Kodi_2.jpg)
- TVHClient
![alt text](https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/Images/TVHClient.jpg)
- Live Channels
![alt text](https://raw.githubusercontent.com/davidmuma/EPG_dobleM/master/Images/Live_Channels.jpg)