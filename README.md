# PRÁCTICA 10

## PLUGINS MÁS UTILIZADOS
Agunos de los plugins y widgets más usados y que más me han llamado la atención son los siguientes:

- **Contact Form 7:** Este plugin puede gestionar múltiples formularios de contacto. Además puedes personalizar la forma y los contenidos de una manera muy sencilla.

- **Yoast WordPress SEO Plugin:** Este plugin es uno de los más populares entre los Webmasters y mejora el SEO de tu blog en todos los aspectos necesarios. Además de la optimización técnica, este plugin te ayuda a escribir un mejor contenido de cara a los motores de búsqueda.

- **Jetpack:** Jetpack es un plugin muy popular que simplifica la gestión de los sitios WordPress dando estadísticas de los visitantes, servicios de seguridad y ayudándote a conseguir más tráfico.

- **Revslider:** Es un plugin que presenta tu contenido de una forma muy elegante, ya sea mediante un Slider, carrusel, escenas o bien mediante una Front Page total. Su editor visual te permitirá contar tu historia de una manera simple y rápida.

- **W3 Total Cache:** Este plugin mejora la experiencia de usuatrio de tu sitio incrementando el rendimiento del mismo, reduciendo los tiempos de carga.

- **Visual Composer:** Visual Composer es el editor visual más usado por los webmaster en sus blogs y te permite una experiencia de creación WYSIWYG (lo que ves es lo que tienes) real, donde vas viendo todo lo que creas al instante y no tienes que diseñar a ciegas apoyándote siempre en el uso de una vista previa.

## INSTALACIÓN DE UN TEMA
Yo en mi caso he instalado el tema `vantage` y para esto me he cambiado al directorio `/var/www/html` y una vez dentro he ejecutado el siguiente comando para instalarlo y activarlo: 
```
sudo wp theme install vantage --activate --allow-root
``` 

Si quisieramos activar un tema ejecutamos el siguiente comando:
```
sudo wp theme activate nombre-tema --allow-root
```

Para eliminar un tema ejecutaríamos el siguiente comando:
```
sudo wp theme delete nombre-tema --allow-root
```

Para listar los temas instalados ejecutamos:
```
sudo wp theme list --allow-root
```

Para eliminar los temas que están inactivos ejecutamos el siguiente comando:
```
sudo wp theme delete $(wp theme list --status=inactive --field=name) --allow-root
```

También es importante saber como actualizar los temas que tenemos instalados y esto sería de la siguiente forma:
```
sudo wp theme update --all --allow-root
```

## INSTALACIÓN DE UN PLUGIN
Yo en mi caso he instalado los temas que se ven en la captura de pantalla de debajo.

![](https://raw.githubusercontent.com/joseean29/Practica-10-IAW/main/image/misplugins.PNG)

Esto lo he hecho de la siguiente forma:
```
- sudo wp plugin install bbpress --activate --allow-root

- sudo wp plugin install duplicator --activate --allow-root

- sudo wp plugin install cookie-law-info --activate --allow-root

- sudo wp plugin install jetpack --activate --allow-root

- sudo wp plugin install seo-wordpress --activate --allow-root
``` 

Si quisieramos desactivar un plugin ejecutamos el siguiente comando:
```
sudo wp plugin deactivate nombre-plugin --allow-root
```

Para eliminar un plugin ejecutaríamos el siguiente comando:
```
sudo wp plugin delete nombre-plugin --allow-root
```

Para listar los plugins instalados ejecutamos:
```
sudo wp plugin list --allow-root
```

Para eliminar los plugins que están inactivos ejecutamos el siguiente comando:
```
sudo wp plugin delete $(wp plugin list --status=inactive --field=name) --allow-root
```

También es importante saber como actualizar los plugins que tenemos instalados y esto sería de la siguiente forma:
```
sudo wp plugin update --all --allow-root
```


## CREDENCIALES
**[IP de mi sitio](http://3.235.181.10)**
```
Usuario: admin
Contraseña: admin
```
