# terminal
Bases de terminal y comandos que vimos en el curso de terminal

Ls= ve comandos cd cambia de directorio -l es para ver formato completo -lh lectura humana en kilobytes -la es archivos ocultos -lS documentos ordenados por tamaño -lr de reversa, tree despliega todos los doc como árbol -L [n] expresa el árbol en los niveles que quieres
Pwd te dice en que directorio estas. 
Ruta relativa es . y .. 
. es para ir a un documento 
.. es regresarte al doc anterior
Mkdir es crear directorio
Touch para crear archivo
Cp copy
mv move y renombrar archivos 
rm remove y con -i es interactivo
rm -r es para remover directorios
head muestra la cabecera de archivo de texto (10)
-n n muestra las líneas que quieras de texto
tail muestra las ultimas 10 de texto
less muestra todo el archivo de texto: con espacio saltas rápido con / buscas una palabra y para salir es con Q
xdg-open abre el documento de texto
Alias es para crear comandos rápidos por ejemplo
Alias l=”ls -lh” y al presionar l se automatiza y se hace solo el ls -lh
Man es para manuales 
Info  es similar pero mas resumida
Whatis es para saber que hace o que es un comando en especifico
--help te ayuda a saber que hace
Ls * es para buscar archivos con especificaciones
Ls *abc es para buscar todo lo que esta adelante
Ls abc* es para buscarlo similitudes antes del asterisco
Ls abc? Es para buscar solamente que tengan un carácter después (entre mas signos mas datos)
ls [[:upper:]]* es para buscar lo que tenga mayúsculas (solo archivos)
ls -d [[:upper:]]* para carpetas
y se puede cambiar a lower. Ls [xyz]* es para buscar que contengan esas letras
ls abc > xyz se redirige a donde quieras (archivos)
ls abc >> xyz es para acumular
| es para poder pasar comandos por comandos como cadena de comandos redirigir y hacer múltiples cosas 
Tee hace lo mismo que mayor que ósea redirige
Correr comandos de cadena síncrona con ;
&& es que si se realizo el comando anterior realizara el sig
|| or si se ejecuta el pasado no le importa igual hará el sig
Ls -l dice los permisos del texto
Chmod cambia los permisos de ese archivo
$home es una variable de home te lleva a home y se puede mesclar con cd $HOME
$PATH tiene las rutas de los binarios que ejecutan el sistema
Find permite encontrar un archivo y se debe de poner la ruta desde donde se pone a buscar
find ./ -name file
-type f= file
-type d= documents
Find ./ -size 20M por tamaño
Grep es para encontrar coincidencias en un archivo
Grep towers movies.csv
Grep -c cuanta ocurrencia hay en un archivo 
Grep -c the movies.csv (1013)
Grep -ci ignora si es mayus o minus
Grep -v es todas las películas que no coincidan 
Grep -vi towers
Wc cuenta cuantas palabras hay, primer valor es líneas de archivo, segundo cuantos caracteres y tercero número de bits L ,W, C en ese orden (wc -l)
Ifconfig demuestra toda la información de red
Ping es para saber si una pagina web esta funcionando
Curl te da el documento html
Wget trae de internet 
Traceroute te da la ruta a todas las computadoras para conectarte a la pagina web
Netstat -i te muestra los dispositivos de red
Tar para comprimir -c (comprimir) -v(muestre ver lo que hace en la terminal) -f(comprimir el file)
-z lo comprime en un formato de gzip
-x es para descomprimir
Zip comprimir
Unzip descomprimir
Ps para ver que procesos se están corriendo
Top muestra los procesos que están uisando mas recursos
H muestra todos los comandos que podría utilizar
Kill mata procesos
Ctrl z para el proceso
Jobs ve todos los procesos de background
Fg 1 se utiliza para mover a foreground el proceso el cual se le da a la izq un numero de trabajo
Ctrl D termina proceso
Bg 1 mueve a background algo
Vi y vim son editores de texto en la terminal
Para salir es :Q
I es para insertar y / para buscar
