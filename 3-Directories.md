# Archivos

**Archivo:** Es la estructura básica empleada para almacenar información.

**Directorio:** Se refiere a la ubicación donde se almacenan los archivos; puede considerarse un contenedor para dichos archivos.

***

# Normas a Seguir

- En Linux, es esencial respetar el formato y los nombres de archivos o directorios, lo que incluye el uso correcto de mayúsculas y minúsculas. Por ejemplo, si creamos un archivo llamado **Cisco.txt** y luego otro llamado **cisco.txt**, Linux no reemplazará el segundo archivo por el primero, ya que los considera distintos.

  - El nombre de un archivo en Linux no debe exceder los 255 caracteres.

  - Se permite el uso de casi cualquier carácter en los nombres de archivo, excepto la barra (/). Sin embargo, se recomienda evitar los siguientes caracteres:

**= \ ~ (tilde) “ * # ; - ? [] () ! & <> |**. Aunque se pueden utilizar, no es aconsejable.

***

# Tipos de Archivos

- **Archivos Ordinarios (-):** Contienen datos como texto, imágenes, archivos PDF, entre otros.

- **Directorios (d):** Contienen otros archivos, organizando la estructura de almacenamiento.

- **Dispositivos:** Representan hardware.
  - **(c):** Dispositivos de carácter, como impresoras.
  - **(b):** Dispositivos de bloque, como discos duros.

- **Enlaces (l):** Proporcionan acceso a otros archivos.

***

# Estructura de Directorios

<img title="script1" alt="script" src="/img/directories.jpeg">

**/bin:** Contiene comandos esenciales (por ejemplo, pwd, clear, passwd, zip).

**/boot:** Almacena los archivos necesarios para el arranque del sistema.

**/dev:** Representa dispositivos, como discos duros y otros periféricos.

**/etc:** Contiene la configuración del sistema, incluyendo redes y aplicaciones instaladas.

**/home:** Directorio personal de los usuarios, donde se encuentran sus archivos y configuraciones.

**/lib:** Almacena bibliotecas compartidas requeridas por el sistema.

**/media:** Facilita la conexión con dispositivos extraíbles, como unidades USB.

**/mnt:** Punto de montaje para discos adicionales.

**/opt:** Utilizado para instalar software adicional.

**/sbin:** Contiene comandos de administración del sistema que requieren privilegios de root (ej. Adduser, ifconfig, userdel).

**/tmp:** Almacena archivos temporales generados por aplicaciones.

**/usr:** Incluye programas y archivos de datos, como el comando ls que también se encuentra en /bin.

**/var:** Almacena archivos variables, que cambian con el tiempo.

**/root:** Directorio del usuario root.

**/proc:** Contiene información sobre procesos y el estado del sistema en tiempo real.
