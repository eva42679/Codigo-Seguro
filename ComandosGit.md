Ver el estado de nuestros archivos:  

git status 

Trackear nuestros archivos: 

Los untracked files son aquellos archivos que no están seguidos por git. Para poder agregarlos utilizamos el comando: 

git add -A 

Este comando añade todos los archivos que no estan trackeados por git. 

Si añadimos por error un archivo a git utilizamos este comando: 

git rm --cached .nombrearchivo 

Commitear un archivo:  

Para poder ver todos los archivos que tenemos commiteados usamos este comando: 

git log  

Clonar un repositorio ya creado de github:  

git clone urldelrepositorio 

Podemos ver la url de nuestro repositorio desde la página de github:  

Si accedemos a nuestro repositorio usando:  

cd nombrerepositorio/ 

Y luego hacemos git log podremos ver todos los commit de los usuarios. 

Modificar un archivo en el Working Directory:  

Si modificamos un archivo dentro de nuestro directorio y hacemos un git status podemos ver como aparecerá nuestro archivo modificado pero no commiteado.  

Si utilizamos el comando:  

git diff  

Podemos ver los cambios que se han hecho respecto al anterior documento.