# Archives 

**Archive :** is the basic structure used to store information 

**Directory :** is where we store the archives , or we can say that the directory is the container of archives

***
# Rules to Respect

- In Linux we should respect the format and the name of file or directory , i mean respecting upper case and lower case ( mayúsculas y minúsculas ) , For exmaple we did create a file called **Cisco.txt** and then i did create another one called **cisco.txt** to replace the first one , so Linux does not replace the second file by the first file because he detect that they are different's
 
  - The file name in linux cannot exceed 255 characters
 
  - The name of a file can use any character, except */* ( slash ) , Although it is not recommended to use:
    
**= \ ~ (tilt) “ * # ; - ? [] () ! & <> |** ,  we can use them in the file name but it's not recommendable 


***


# Types of Archives

- **Ordinary files (-)**: They contain text, images, pdf, etc.

- **Directories (d)**: Contain other files.

- **Devices**: They represent devices.
**(c)**: Character devices. Example: **Printer**
**(b)**: Block devices. Example: **Hard drive**

 - **Links (l)**: They represent access to other files.

***

# Directories Tree

<img title="script1" alt="script" src="/img/directories.jpeg">

**/bin** : Over here we do find all esentials Commands as ( pwd , clear , passwd, zip , ...... )

**/boot** : files that ystem need to boot ( inicio )

**/dev** :device ( dispositivos ) as hard disk , .....

**/etc** : The configuration of the system , over here wher we can configure the network , to check dns , the configuration of DOwnloaded Applicaction , apt , .....

**/home** : where the users live , basicly is where every created user (included their directories) in the OS located .

**/lib** : Shared Library files ( libreria compartida)

**/media** : responsible for the connection with removable devices such as usb 

**/mnt** : here the disks are mounted ( montar los discos )

**/opt** :

**/sbin** : Root Commands tht we should execute it as root  as  ( Adduser , ifconfig , userdel ... ) .

**/tmp** : Temporary Files

**/usr** : we can find games and variables files , for example we have a command ls in /bin so we gonna find him again as the same in /usr/bin 

**/var** : Variable files

**/root** : is the Root by himself

**/proc** : everything we do for the system is saved there
