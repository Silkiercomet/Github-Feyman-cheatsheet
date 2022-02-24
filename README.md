# Github Feyman stylesheet

## que es Github

es un sistema de control o un controlador de versiones

## que es un controlador de versiones 

guarda la version inicial de nuestro programa y todas las que subamos despues, de tal forma de que podamos siempre volver por referencia o restaurar una version anterior

## clonar un repositorio

desde el repositorio podemos darle click a la opcion de clonar y usando los comandos "git clone (repo dir) traeremos el repositorio a nuestra maquina y esta guardara en un archivo especial todos las modificaciones que hagamos y las grabara si usamos el comando " git commit -M "titulo del mensaje" -M "cuerpo del mensaje" " y los cambios seran aplicados a nuestra copia local 

## agregar un archivo al repo

si un repositorio es clonado git seguira los cambios hechos a los archivos que tiene en el origen, pero si creamos un archivo nuevo, este dira "untracked" lo que significa que git no lo tiene en su directorio de archivos y no lo esta siguiendo, para gregarlo usamos el comando " git add (nombre del archivo) "

tambien se puede usar "git add ." que agregara todos los cambios y archivos no rastreados, pero no agregara cambios que incluyan lineas eliminas o archivos eliminados

con el uso del comando "git push origin main" agregaremos los cambios a la rama principal de nuestro repositorio, si siempre se haran los push a la misma direccion podemos definir al rama como upstream asi "git push u- origin main"

## crear un repo localmente

al crear una aplicacion de manera local esta no seguira los cambios aplicados como si se tratara de un clon con un repo de origen, para hacerlo se debera ejecutar el comando "git init" y esto creara el archivo que guardara los cambios hechos, este no estara conectado a ningun lado, solo existira localmente para vincularlo con un repo exterior usamos el comando "git remote add origin (direccion del repo)" de esta manera se agregara un repo que sera usado como referencia de origen fuera de nuestro ambiente local.

## ramas o braches

branches son distintas ramas que divergen de el tronco (nuestro canal principal) de nuestro repositorio, nos permite aplicar y testear features en nuestro codigo sin cambiar nada en el tronco de nuestro repo, avitando que lo fusionemos con codigo dañado

usamos el comando "git branch (nombre de la branch)" para crear una nueva rama en nuestro repo y el comando "git checkout (nombre de la branch)" para movernos entre nuestras ramas, con "git branch" podemos ver las ramas disponibles

si se muestra una M en el nombre del archivo es para señalar de que un archivo de una brach a sido modificado 
