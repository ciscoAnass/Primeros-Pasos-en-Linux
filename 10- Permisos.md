# Identificación de Usuario

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `id`  | Muestra información del identificador del usuario  | `id [nombre_usuario]` ej: `id ciscoanass` | 

***
# Introducción a Permisos
- **r** : read (leer)
- **w** : write (escribir)
- **x** : execute (ejecutar)

| Permisos  | Función  |  
|---|---|
|  `r`  | Permite visualizar el contenido del directorio sin modificar o eliminar archivos. Solo se puede usar el comando `ls`. |  
|  `w`  | Permite escribir y eliminar archivos en el directorio (debe estar combinado con `rw`, `rwx` o `rx`). | 
|  `x`  | Permite acceder al directorio sin la capacidad de crear archivos. |  

***
# Otorgar Permisos Manualmente

| Opción  | Función  | Sintaxis   | 
|---|---|---|
|  `chmod u`  | Otorga o quita permisos al usuario  | `sudo chmod u+rx,u-w fichero1` | 
|  `chmod g`  | Otorga o quita permisos al grupo | `sudo chmod g+rx,g-w fichero1` | 
|  `chmod o`  | Otorga o quita permisos a otros | `sudo chmod o+rx,o-w fichero1` | 
|  `chmod a`  | Otorga o quita permisos a todos (usuarios, grupos, otros) | `sudo chmod a+rx,a-w fichero1` | 

 ***
# Permisos Numéricos

| Opción  | Función  | Sintaxis   | 
|---|---|---|
|  `chmod 732` | Otorga permisos numéricos a todos (incluidos grupos y otros)   | `sudo chmod 732` >>> `rwxr-x-wx` | 

**Diccionario:**
- **r=4** 
- **w=2**
- **x=1**

***
# La Máscara (umask)

**La máscara**: permite establecer permisos predeterminados al crear archivos o directorios.

| Opción  | Función  | Sintaxis   | 
|---|---|---|
|  `umask`  | Ver los permisos por defecto | `umask` | 
|  `umask [num]`  | Modificar los permisos por defecto | `umask [num]` | 

***
# Cambiar Propietario y Grupo

| Opción  | Función  | Sintaxis   | 
|---|---|---|
|  `chgrp`  | Cambiar el grupo del archivo o directorio | `chgrp grp2 fichero1` | 
|  `chown` | Cambiar el usuario del archivo o directorio | `chown user2 fichero1` | 
