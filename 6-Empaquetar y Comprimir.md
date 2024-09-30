# TAR

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| -cvf   | Empaquetar archivos en un único archivo TAR  | `tar -cvf curriculo.tar documento1.pdf documento2.pdf documento3.pdf`  | 
| -tvf  | Visualizar el contenido del archivo TAR   | `tar -tvf curriculo.tar`  | 
| -xvf | Extraer el contenido del paquete TAR   | `tar -xvf curriculo.tar`  | 
| -C | Extraer el paquete TAR en una ubicación específica | `tar -xvf curriculo.tar -C /ruta/destino`  | 

***

# Gzip

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `gzip`  | Comprimir un archivo y eliminar el original | `gzip documento.html` | 
| `gzip -k` | Comprimir un archivo y mantener el original | `gzip -k documento.html`  | 
| `gzip -l` | Visualizar el archivo comprimido  | `gzip -l documento.html.gz`  | 
| `gzip -d` | Descomprimir el archivo a su estado original | `gzip -d documento.html.gz` | 

***

# ZIP y UNZIP

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `zip`  | Comprimir un archivo en formato ZIP | `zip archivo.zip archivo1.html archivo2.html`  | 
| `zip -r` | Comprimir un directorio en formato ZIP | `zip -r carpeta.zip carpeta`  | 
| `unzip -v` | Visualizar el contenido del archivo ZIP  | `unzip -v carpeta.zip`| 
| `unzip -d` | Descomprimir el archivo ZIP en una ubicación específica | `unzip carpeta.zip -d /home/usuario/carpeta_destino` | 

***

# TAR.GZ

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `tar -zcvf`  | Comprimir y empaquetar un archivo en formato tar.gz | `tar -zcvf documentos.tar.gz archivo1.txt archivo2.txt archivo3.txt` | 
| `tar -ztvf` | Visualizar el contenido del paquete comprimido tar.gz | `tar -ztvf  documentos.tar.gz` | 
| `tar -zxvf` | Descomprimir un paquete tar.gz | `tar -zxvf documentos.tar.gz` | 
| `tar -zxvf -C` | Descomprimir el paquete en una ubicación específica | `tar -zxvf documentos.tar.gz -C /home/usuario/carpeta_destino` | 

***

# TAR.BZ2

| Opción  | Función  | Sintaxis   | 
|---|---|---|
| `tar -jcvf`  | Comprimir y empaquetar un archivo en formato tar.bz2 | `tar -jcvf archivos.tar.bz2 archivo1.txt archivo2.txt archivo3.txt` | 
| `tar -jtvf` | Visualizar el contenido del paquete comprimido tar.bz2 | `tar -jtvf  archivos.tar.bz2` | 
| `tar -jxvf` | Descomprimir un paquete tar.bz2 | `tar -jxvf archivos.tar.bz2` | 
| `tar -jxvf -C` | Descomprimir el paquete en una ubicación específica | `tar -jxvf archivos.tar.bz2 -C /home/usuario/carpeta_destino` | 

***
