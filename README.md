| Comando | Descripción | Ejemplo de Uso  |
|  :---:  |   :---:  |  :---:  |
| man  |mostrar el manual de usuario de cualquier comando  | $ / usr / share / man.|
|sudo  |  Es un comando que ejecuta un indicador elevado sin necesidad de cambiar su identidad.| $ sudo apt-get update  |
| su | acrónimo de superuser do o replace user do , es un comando que ejecuta un indicador elevado sin necesidad de cambiar su identidad.| $ su  |
| whoami | muestra el nombre del usuario actualmente conectado. | whoami [OPTION] |
| more | muestra el nombre del usuario actualmente conectado. |MORE [/E [/C] [/P] [/S] [/Tn] [+n]] < [unidad:][ruta]archivo |
|tail |Es el complemento del comando de cabeza . El comando de cola, como su nombre lo indica, imprime el último número N de datos de la entrada dada. | cola [OPCIÓN]... [ARCHIVO]...|
|tail -n| Imprime las últimas líneas 'num' en lugar de las últimas 10 líneas. num es obligatorio especificarlo en el comando; de lo contrario, muestra un error. |  tail -n 3 estado.txt |
|pwd|  Mostrar la ruta del directorio de trabajo actual. |  $ pwd|
|ls | es uno de los muchos comandos de Linux que permiten a un usuario listar archivos o directorios| $ ls 
|head -n| Contenido de la celda  | Contenido de la celda  |
|cp|copiar el contenido  ya sea de carpeta o archivo | cp [Origen] [Destino]  |
|alias| Contenido de la celda  | Contenido de la celda  |
|mv| para mover  carpetas o archivos a otro sitio  | mv [Origen] [Destino]|
|rm| Elimina un directorio (siempre y cuando esté vacío).|  rm  [Origen] |
|Creación de usuarios: useradd| Con el comando useradd podemos crear usuarios desde el terminal.  | useradd [options] nombre_de_usuario /useradd asolano |
|mpasswd| para generar una contraseña aleatoria en sistemas operativos similares a Linux/UNIX.  | $ makepasswd --chars 16 |
|archivo largo \|  less | Contenido de la celda  | Contenido de la celda  |
|mkdir|crear directorios.| $ mkdir [Destino] / mkdir /home/desktop/lista de alumnos.txt|
|ls -l| muestra la lista de archivos con formato largo y con información detallada (tamaño, usuario, grupo, permisos etc.). | ls -l / ls -l [Origen] |
|telnet towel.blinkenlights.nl| Contenido de la celda  | Contenido de la celda  |
| ps -aux | Contenido de la celda  | Contenido de la celda  |
|ps -aux \| grep “firefox”| Contenido de la celda  | Contenido de la celda  |
|ip addr| Contenido de la celda  | Contenido de la celda  |
|top|  Contenido de la celda |     ontenido de la celda    | 
|chmod|Modifica los permisos de uno o más archivos o directorios.|chmod [Opciones] [permiso_descripción] archivo|
|cat|Muestra el contenido de un archivo utilizando la salida estándar (pantalla).|cat [-benstvA] archivos|
|find|Muestra una lista con los archivos que coinciden con un criterio especifico.|find [ruta] [opciones]|
|grep|Busca en uno o más archivos las líneas que coincidan con una expresión regular (modelo de búsqueda).|grep [opciones] modelo archivos|
|touch|permite actualizar los tiempos de acceso y modificación de los archivos especificados. ///  La mayoría de las veces no se utilizará touch para modificar las fechas de los archivos, sino para crear nuevos archivos vacíos|touch new_file_name|
|	/Bin|Este es un directorio donde almacenamos los binarios por lo que es estático y ayuda para la que haga el almacenamiento de lo que el usuario ejecuta.||
|	/Boot|El Boot es que contine los ejecutables e iguala que el /Bin es estático solo que /Boot es para el arranque del sistema al cual están asociados.||
|/Dev|Con el /Dev es un directorio el cual tiene los dispositivos que son de almacenamiento. Es importante indicar que es podría ser un disco duro, una memoria de USB, el lector de discos CDROM (cabe indicar que este deberá estar con una conexión en el equipo), entre otros. También sirve para realizar particiones al disco duro mediante comandos.||
|	/Etc|El Etc es un almacenamiento el cual se encarga por la configuración ya sea para los componentes para el sistema operativo sino también para las aplicaciones o programas a instalar.||
|	/Home|Este se directorio se encarga del almacenamiento de los archivos que el usuario requiera ir guardando por ejemplo lista de canciones, videos, archivos, fotos, etc.||
|/Lib|Este archivo se encarga de las bibliotecas más esenciales para ser ejecutadas de manera correcta por los binarios.||
|/Media|Es el punto de montaje con el que todos los volúmenes lógicos ya sean temporales como externas (memorias USB), entre otras particiones de disco.||
|	/Opt|El Opt en algún modo podría ser básicamente una extensión del directorio al igual de todos aquellos archivos que son de para lectura y que de igual manera son parte de programas autocontenidos.||
|	/Proc|Este directorio son procesos y aplicaciones que contienen y estos estarán ejecutándose en determinados momentos en el sistema, pero estos no guardan en nada realidad sin no almacena los archivos que son virtuales a lo que decimos que el contenido de estos directorios es similar a nulo.||
|	/Root|Es similar al directorio /Home. La diferencia esta se encuentra dentro de /home todas sus carpetas y subcarpetas, definimos que siempre está en su propia carpeta, pero estando en raíz del sistema indirectamente.||
|	/Srv|Este sirve para el almacenamiento de los archivos y también directorios que sean relativos con los servidores que entre sus condiciones estas puedan estar instalados en si de mismo sistema, como servidor web (FTP, CVS) por ejemplo||
|	/Sys|Es similar a / proc al cual contiene archivos que sean provenientes de la información del kernel y es relativa sobre eventos del SO (Ssistema Operativo).||
|	/Tmp|Sirve para almacenamiento de todos los archivos temporales de todo tipo los cuales sea de elementos sobre sistema, así como diferentes aplicaciones por ejemplo los navegadores de Internet (Firefox, Chromium o Chrome.)||
|	/Usr|Estos directorios actualmente nos ayudan para almacenamiento sobre todos los archivos ya su lectura, así como relativos. Además, incluyen software instalado que obtenemos por medio de paquetes de cada distribución. ||
|	Var|El Var son archivos con información sobre sistema, por ejemplos archivos de logs, correos electrónicos de los usuarios, también bases de datos, el cache con su información que almacena. ||
|exit| Con él, puedes terminar una sesión de shell y, en la mayoría de los casos, cerrar automáticamente el terminal que estás utilizando:|$ exit|
| unzip | Permite extraer el contenido de un archivo .zip desde el terminal.  |    unzip images.zip |
|apt, yum, pacman|Independientemente de la distribución de Linux que utilices, es probable que uses gestores de paquetes para instalar, actualizar y eliminar el software que utilizas a diario.| sudo apt install [paquete a instalar] o sudo yum install [paquete a instalar]o  sudo pacman -S [paquete a instalar] |
|echo | Muestra el texto definido en el terminal |echo "Hello Wordl"|
|Kill| termina o mata un proceso  | kill [proceso]|
|ping   |La utilidad de terminal de red más popular que se utiliza para probar la conectividad de la red| ping [paquete]   / ping google.com|
|Neofetch| Herramienta CLI (command-line interface) que muestra información sobre tu sistema -como la versión del kernel, el shell y el hardware- junto a un logotipo ASCII de tu distribución de Linux | sudo noeftch |
|reboot| reiniciar el sistema | # reboot now|
|df -h |mostrar una lista de las particiones montadas| # df -h|
|yum | Descargar e Instalar un paquete rpm.| [paquete a instalar] |
|mkswap|crear fichero de sistema swap.| mkswap [Origen]   o  mkswap /dev/hda3 | 
