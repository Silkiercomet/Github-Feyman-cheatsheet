# Github Feyman stylesheet

## que es Github

es un sistema de control o un controlador de versiones

## que es un controlador de versiones 

guarda la version inicial de nuestro programa y todas las que subamos despues, de tal forma de que podamos siempre volver por referencia o restaurar una version anterior

## clonar un repositorio

desde el repositorio podemos darle click a la opcion de clonar y usando los comandos "git clone (repo dir) traeremos el repositorio a nuestra maquina y esta guardara en un archivo especial todos las modificaciones que hagamos y las grabara si usamos el comando " git commit -M "titulo del mensaje" -M "cuerpo del mensaje ""

## agregar un archivo al repo

si un repositorio es clonado git seguira los cambios hechos a los archivos que tiene en el origen, pero si creamos un archivo nuevo, este dira "untracked" lo que significa que git no lo tiene en su directorio de archivos y no lo esta siguiendo, para gregarlo usamos el comando " git add (nombre del archivo) "

tamnien se puede usar "git add ." que agregara todos los cambios y archivos no rastreados, pero no agregara cambios que incluyan lineas eliminas o archivos eliminados
