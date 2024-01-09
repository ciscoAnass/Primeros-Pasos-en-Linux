# ID

| Option  | function  | syntax   | 
|---|---|---|
|  id  | Nos muestra información del identificador del usuario  | id [username] >>>> id ciscoanass | 

***
# Introduccion
**r** : read >>> leer
**w** : write >>> escribir
**x** : execute >>> ejecutar

| Permisos  | function  |  
|---|---|
|  r  | podemos visualizar el directorio sin poder de modificar o eliminar osea solo podemos hacer #ls  |  
|  w  | podemos escribir y eliminar archivos en el directorio ( debe estar combinada  rw or rwx or rx )  | 
|  x  | Permite acceder aldirectorio sin pdoder de crear archivos  |  

***
# dar permisos de manera manual

| Option  | function  | syntax   | 
|---|---|---|
|  chmod u  | mandar o quitar los permisos al usuario  | sudo chmod u+rx,u-w fichero1 | 
|  chmod g  | mandar o quitar permisos al grupo | sudo chmod g+rx,g-w fichero1 | 
|  chmod o  | mandar o quitar permisos a los otros | sudo chmod o+rx,o-w fichero1 | 
 
 ***
 #  Permisos Numericos


| Option  | function  | syntax   | 
|---|---|---|
|  chmod 732 |dar permisos de manera numerica a todos incluid los grupos y ...   |sudo chmod 753 >>> rwxr-x-wx | 


 **Diccionario :** 
 - **r=4** 
- **w=2**
- **x=1** 

***

# La mascara : umask

**La mascara** : es para crear permisos poe defecto sin necesidad a modificar los permisos por cada creacion de ficheros o directorios.

| Option  | function  | syntax   | 
|---|---|---|
|  umask  | ver los permisos por defecto | umask | 
|  umask [num]??????  | modificar los permisos| umask | 

***


# chown , chgrp


| Option  | function  | syntax   | 
|---|---|---|
|  chgrp  | cambiar el grupo del fichero o el directorio | chgrp grp2 fichero1 | 
|  chown |cambiar el usuario del fichero o el directorio| chown user2 fichero1 | 
