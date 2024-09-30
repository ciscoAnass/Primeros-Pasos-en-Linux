# SORT

**Sort:** Permite ordenar el contenido de uno o varios archivos.

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `-n`  | Ordenación numérica  | `sort -n telefonos.txt` | 
| `-u` | Elimina las líneas repetidas | `sort -n -u telefonos.txt`  | 
| `-r` | Ordena en orden inverso | `sort -n -r telefonos.txt` | 
| `-k` | Especifica el número de campo utilizado para ordenar el archivo | `sort -k3 telefonos.txt` | 
| `-t` | Define el separador de campos | `sort -t "," -k5 alumnos.txt`  | 

***

# tr

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `tr`  | Reemplazar caracteres | `cat hp.txt | tr "a" "t"` | 
| `tr -s`  | Elimina caracteres repetidos (por ejemplo, "localhostt" se convierte en "localhost") | `cat hp.txt | tr -s "t"` | 
| `tr -c` | Reemplaza todos los caracteres con otro, excepto el carácter seleccionado | `cat hp.txt | tr "a-z" ";"`   | 
| `tr -d` | Elimina caracteres | `echo "anass" | tr -d "a"` |

***

# sed

**sed** se utiliza para reemplazar un carácter por otro (similar al comando en vim: `:%s/hello/bye/g`).

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `sed` | Reemplaza un carácter por otro | `sed 's/hello/bye' datos.txt` |

***

# grep

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `grep -i` | Ignora mayúsculas y minúsculas | `grep -i "palabra" archivo.txt` |
| `grep -v` | Elimina las líneas que contienen la palabra o frase buscada | `grep -v "palabra" archivo.txt` |
| `grep -c` | Cuenta el número total de líneas que contienen la palabra buscada | `grep -c "palabra" archivo.txt` |
| `grep -r` | Busca recursivamente en un directorio | `grep -r "palabra" /ruta/directorio` |

***

# CUT

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `cut -d` | Selecciona una parte del texto | `cut -d ":" -f 1,2` |

***

# PASTE

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `paste -d` | Combina dos archivos en uno | `paste -d ":" file1 file2` |

***

# AWK

| Sintaxis  | Descripción  |
|---|---|
| `awk -F: '{print}' fichero1.txt` | Funciona como `cat`, mostrando todo el archivo. |  
| `awk -F: '{print $5 "-" $1}' fichero1.txt`  | Muestra el campo 5 y el campo 1 del archivo. |  
| `awk -F: '$1==18 {print $2}' fichero.txt`  | Si el campo 1 es igual a 18, extrae el campo 2.  |  
| `awk -F: '$1=18 {print $2 "-" $1}' fichero.txt`   | Reemplaza el campo 1 por 18 en todas las líneas. |  
| `awk -F: '$4>=18 && $4<=64 {print $1}' fichero` | Extrae el campo 1 relacionado con el campo 4 que está entre 18 y 64. |  

***

# pr

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `pr`  | Formatea el archivo | `pr archivo.txt` | 
| `pr -n "título"`  | Agrega un título al archivo en todas las páginas | `pr -n "Título del Archivo" archivo.txt` | 
| `pr -d` | Doble espacio entre líneas | `pr -d archivo.txt` | 
| `pr -w` | Establece el ancho de la página en caracteres | `pr -w 80 archivo.txt` |
| `pr -l` | Establece la longitud de la página en líneas | `pr -l 50 archivo.txt` |
| `pr -n` | Numera las líneas del archivo | `pr -n archivo.txt` |
