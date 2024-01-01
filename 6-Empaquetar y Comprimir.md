# Tar


| Option  | function  | syntax   | 
|---|---|---|
| -cvf   | Empaquetar los Ficheros a un fichero unico TAR  | tar -cvf cv.tar anass.pdf ahmed.pdf karima.pdf  | 
| -tvf  | visualizar lo q hay dentro el ficheero TAR   | tar -tvf cv.tar  | 
|  -xvf | Extraer el paquete Tar   | tar -xvf cv.tar  | 
|  -xvf -C | Extraer el paquete Tar  en otro lado | tar -xvf cv.tar  | 




***
# Gzip

| Option  | function  | syntax   | 
|---|---|---|
| gzip  | comprimir el fichero y borrarlo | gzip anass.html | 
| gzip -k | comprimir el fichero y dejarlo tranquilo sin borrarlo   |gzip 0k anass.html  | 
| gzip -l | Visualizar el fichero comprimido  | gzip -l anass.html.gz  | 
| gzip -d | decomprimirlo otra vez a fichero normal   |gzip -d anass.html.gz | 



***

# ZIP , UNZIP

| Option  | function  | syntax   | 
|---|---|---|
| zip  | comprimir un fichero a ZIP | zip html.zip index.html header.html  | 
| zip -r | comprimir un directorio a zip |zip -r folder.zip folder  | 
| unzip -v | Visualizar a lo q hay dentro el zip  | unzip -v folder.zip| 
| unzip -d | decomprimir el fichero zip  | unzip folder.zip -d /home/heidi/carpeta | 


***

# TAR.GZ

| Option  | function  | syntax   | 
|---|---|---|
| tar -zcvf  | comprimir Y empaquetar un fichero a tar.gz | tar -zcvf profesores.tar.gz manolo.txt maria.txt javier.txt | 
| tar -ztvf | Visualizar a lo q hay dentro el paquete comprimido tar.gz |tar -ztvf  profesores.tar.gz | 
| tar -zxvf | descomptimir un paquete | tar -zxvf profesores.tar.gz| 
| tar -zxvf -C / | decomprimir el paquete a un ubicacion exacta  | tar -zxvf profesores.tar.gz -C /home/heidi/1asir | 



***

# TAR.BZ2

| Option  | function  | syntax   | 
|---|---|---|
| tar -jcvf  | comprimir Y empaquetar un fichero a tar.bz2 | tar -jcvf profesores.tar.bz2 manolo.txt maria.txt javier.txt | 
| tar -jtvf | Visualizar a lo q hay dentro el paquete comprimido tar.bz2 |tar -jtvf  profesores.tar.bz2 | 
| tar -jxvf | descomptimir un paquete | tar -jxvf profesores.tar.bz2 | 
| tar -jxvf -C / | decomprimir el paquete a un ubicacion exacta  | tar -jxvf profesores.tar.bz2 -C /home/heidi/1asir | 

***


