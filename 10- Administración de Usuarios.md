# Administración de Usuarios 👥


## Creación de usuarios

Para crear un nuevo usuario:

```bash
sudo useradd -m username
```

El flag `-m` crea el directorio home del usuario.

## Modificación de usuarios

Para modificar un usuario existente:

```bash
sudo usermod [opciones] username
```

Ejemplo: Cambiar el shell del usuario
```bash
sudo usermod -s /bin/bash username
```

## Eliminación de usuarios

Para eliminar un usuario:

```bash
sudo userdel -r username
```

El flag `-r` elimina también el directorio home del usuario.

## Gestión de grupos

Crear un nuevo grupo:
```bash
sudo groupadd groupname
```

Añadir un usuario a un grupo:
```bash
sudo usermod -aG groupname username
```

## Permisos de usuario

Ver los permisos de un archivo:
```bash
ls -l filename
```

Cambiar los permisos:
```bash
sudo chmod [opciones] filename
```

## Cambio de contraseñas

Cambiar la contraseña de un usuario:
```bash
sudo passwd username
```
