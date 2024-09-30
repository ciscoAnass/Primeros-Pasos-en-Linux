# Scripts

Primero, hablemos de algunas reglas que debemos respetar:

1. **#!/bin/bash**: Siempre debemos incluir esta línea como la primera en cada archivo de script. Esto indica que el script debe ser ejecutado con el intérprete de Bash.

2. **.sh**: El archivo de script debe tener siempre la extensión .sh para indicar que es un script de shell.

3. Para ejecutar el archivo de script, utilizamos el siguiente comando:

    ```bash
    ./fichero1.sh
    ```

   **Nota**: Asegúrate de que el archivo tenga permisos de ejecución. Puedes otorgar permisos con el siguiente comando:

    ```bash
    chmod +x fichero1.sh
    ```



***
## Vamos a crear nuestro primer script básico

<img title="script1" alt="script" src="/img/script1.png">

- En la imagen podemos ver que hemos creado un archivo de script y hemos incluido **#!/bin/bash** en la primera línea. En la segunda línea, agregamos un comentario (autor) del archivo, que es opcional; puedes incluirlo o no. Finalmente, hemos escrito **echo "Hello, World!"**, lo que significa imprimir "Hello, World!". Al ejecutar el script, obtenemos "Hello, World!" como resultado de la ejecución.

<img title="execscript" alt="ejecución del script" src="/img/execscript.png">

- Si queremos insertar una línea en blanco en el texto, usamos **\n** (que es similar a `<br>` en HTML).

<img title="skipline" alt="salto de línea" src="/img/skipline.png">

***
# Variables

<img title="script1" alt="script" src="/img/allvalues.png">

- Para crear un Variable , debemos seguir esta sintaxis: `'Palabra clave' = 'Valor'`.

  Por ejemplo:

  > nota=10
  >
  > echo "Has sacado $nota"

- Al ejecutar el script, el resultado será **Has sacado 10** porque `$nota` ha tomado el valor de 10 previamente.

***

- También contamos con una excelente herramienta en scripting llamada **read -p**, que es útil para la automatización de valores cambiantes.

- Por ejemplo: en una empresa tenemos más de 40 usuarios (trabajadores) y cada trabajador tiene un nombre diferente. Si queremos crear un script que, cada vez que inicien sesión, diga **(Hola #Usuario, que tengas un buen día)**, no necesitamos crear 40 scripts, cada uno con un nombre de usuario, porque **read -p** nos ayudará.

- Así que simplemente pondremos:

  > read -p "¿Cuál es tu nombre de usuario? " username
  >
  > echo "Hola $username, que tengas un buen día."

- Básicamente, solo le preguntamos al usuario por su nombre de usuario y, cuando lo ingresa, el script automatiza la respuesta a **(Hola $username, que tengas un buen día)**, lo que permite que cada trabajador reciba una respuesta automatizada con su nombre.

<img title="script1" alt="script" src="/img/readp.png">

<img title="script1" alt="script" src="/img/valuesresult.png">


