# basic-comands-git

### **Antes que nada debes crear una cuenta en github**

```
* Git init: permite iniciar git para nuestro proyecto desde la ubicación donde estamos ubicados.

* Git status: muestra los archivos que aún no han sido agregados a git.

* Git status *: agrega todos los archivos que no han sido agregados  a nuestro espacio de trabajo, si queremos agregar solo 1 reemplazamos el * por el nombre del archivo y su extensión , sin embargo aún no estarán agregados a nuestro repositorio git.

* Git commit : Al principio nos pedirá que ingresemos el correo seguido del usuario en los 2 cosas debemos escribir git config --global user.emal "tucorreo" y luego git config --global user.name "tunick" y listo. 
	
* Git commit -m "descripcion": Guarda los archivos adaptamos a nuestro espacio de trabajo a nuestro repositorio debemos ingresar un mensaje descriptivo para especificar de qué se trata ese commit.
	
* Git log *: Nos muestra los commit que están dentro de nuestro repositorio.
	
* Archivo .gitignore: Para ignorar archivos o carpetas que no serán almacenados en nuestro repositorio debemos crear un archivo sin extensión con el nombre .gitignore dentro de nuestro proyecto y dentro de este archivo debemos ingresar el nombre de la carpeta o el nombre de archivo más su extensión los cuales deseamos ignorar.  Luego solo agregamos dicho archivo con git add y hacemos el commit con su descripción y listo.
	
* Git branch: Crea una nueva rama dentro del proyecto esta llama no es más que una versión alternativa de nuestro proyecto para crear una rama ingresamos el comando git branch "nombre de la nueva versión sin comillas", y para ver las ramas que existen dentro de nuestro proyecto ingresamos el comando git branch. 
Para cambiar de rama utilizamos el comando git checkout "nombre de la branch sin comillas".
``` 

## Ahora a subir nuestro repositorio a github
```	
* Git remote add origin "enlace de tu repositorio en github sin comillas"  y luego con el comando git push -u origin master subimos nuestro proyecto git a nuestro repositorio en git hub.

* Git clone "más enlace de descarga clonado sin comillas" para descargar el proyecto desde git hub
```

### Notas:
```
* Si queremos agregar carpetas en .gitignore a veces es necesario escribir el / de la carpeta
* Commit = cometer
* Branch = ramasa
* Checkout = revisa
```
