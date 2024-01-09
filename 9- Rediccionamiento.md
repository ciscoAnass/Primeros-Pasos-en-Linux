# SORT

**Sort:** nos permite  aordenar el contenido de uno o vario ficheros

| Option  | function  | syntax   | 
|---|---|---|
|  -n  | ordenadcion numerica  | sort -n telefonos.txt | 
| -u | ELimina la lineas repitidas | sort -n -u telefonos.txt  | 
| -r | ordena al inverso de la ordenacion    | sort -n -r telefonos.txt | 
|  -k | el numero de campo utilizado para ordenar el fichero | sort -k3 telefonos.txt | 
|  -t | separador de campos | sort -t "," -k5 alumnos.txt  | 



***

# tr

| Option  | function  | syntax   | 
|---|---|---|
|  tr  | Replazear caracteres con otros | cat hp.txt /tr "a" "t" | 
|  tr -s  | Quita el caracter repitido (localhostt) | cat hp.txt /tr -s "t"| 
| tr -c| replazea todos los caracteres con otro excepto el caracter seleccionado por el comando | car hp.txt \  tr "a-z" ";"   | 
| tr -d |  Elimina caracteres | tar -d "anass" |


***

# sed


es para cambiar un caracter a otro ( en vim es " **:%s/hello/bye/g** " )
es comando es :   **sed 's/hello/bye' datos.txt**

| opcion  | function  | syntax   | 
|---|---|---|
| sed |  remplazea un caracter con otro | sed 's/hello/bye' datos.txt |


***
# grep

| opcion  | function  | syntax   | 
|---|---|---|
| grep -i | ignora mayusculas y minisculas | |
| grep -v | quita la linea q lleva la palabra o el frase q buscamos  | |
| grep -c | nos dice el total de lines q llevan la palabara q nos buscamos | |
| grep -r |  | |


***
# CUT

| opcion  | function  | syntax   | 
|---|---|---|
| cut -d -f | es para seleccionar un parte del texto |  cut -d ":" -f 1,2 |


***
# PASTE

| opcion  | function  | syntax   | 
|---|---|---|
| paste -d | es para adjuntar 2 ficheros en un fichero |  paste -d ":" file1 file2 |

***

# AWK

| syntax  | Descripcion  |
|---|---|
|awk -F: '{print}' fichero1.txt | eso se funciona como 'cat' , basicamente ensenya todo el fichero |  
|awk -F: {print $5 "-" $1} fichero1.txt  | ensenyar el campo 5 y 1 del fichero |  
|awk –F: ‘$1==18 {print $2}’ fichero.txt  | Si el campo1 es igual a 18, extrae el campo 2.  |  
|awk –F: ‘$1=18 {print $2 "-" $1}’ fichero.txt   | Replacea el campo 1 18 por todas las lineas   |  
| awk -F: '$4>=18 && $4<=64 {print $1}' fichero | extrae el campo 1 lo q esta relacionado con el campo 4 q esta menor de 64 y mayor de 18 |  


***

# pr

| Option  | function  | syntax   | 
|---|---|---|
|  pr  | crea formato al fichero | | 
|  pr -n "title"  | crea un titulo al fichero por todas las paginas | 
| pr -d | doble espacio entre linea y otra | | 
| pr -w | Ancho de la página en caracteres | |
| pr -l | Longitud de la página en líneas. | |
| pr -n | crea la numeracion de lineas | |



