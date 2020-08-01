# Bitacora-de-Comandos
<h2>Parametros Generales:</h2>
	<ul>
		<li>Sudo: da permiso de administrador a un comando.</li>
		<li>Apt: paquete que permite instalar software.</li>
		<li>Update: busca actualizaciones disponibles</li>
		<li>Upgrade: ejectua las actualizaciones encontradas (si hay).</li>
  </ul>
<h2>Comandos Generales:</h2>
<ul>
 <li>ls: muestra carpetas dentro de un directorio.</li>
      <h4>Algunos parametros</h4>
			<ul>
      	<li>ls -la: muestra los archivos ocultos</li>
      	<li>ls -l: muestra las carpetas con mas detalles y en el formato de lista.</li>
      	<li>ls (nombre de carpeta): muestra los contenidos dentro del nombre de la carpeta</li>
			</ul>	
  <li>mkdir: se utiliza para crear una carpeta</li>
  <li>Cd: se utiliza para cambiar de directorio</li>
      <h4>Algunos parametros</h4>
			<ul>
      	<li>cd ~ o cd.. : se utliza para volver al directorio home o devolverse de directorio.</li> 
      	<li>cd (nombre de carpeta): pasa al directorio de esa carpeta.</li>
			</ul>		
  <li>touch: crea archivos</li>
      <h4>Ejemplo</h4>
	<ul>
      <li>touch archivo1.txt: crear un archivo de formato .txt llamado archivo1</li>
	</ul>	
  <li>Cat: Muestra el contenido de un archivo.</li> 
  <li>Ps -aux: muestra todos los procesos que están corriendo de momento en el equipo.</li>
  <li>Pstree: muestra los procesos pero con grafica de arbol donde se ven las jerarquias de los procesos.</li>
  <li>| (pipe): se usa para juntar dos comandos. </li>
  <li>grep: busca líneas con un parámetro específico.</li>
	<ul>
      	<h4>Ejemplo</h4>
      	<li>ls | grep archivo1.txt: en lista los archivos en el directorio que se incluyan en su nombre archivo1.txt</li>
	</ul>	
  <li>kill -9: elimina o detiene un proceso</li>
	
  <li>Uname -a: version del kernel.</li> 
  <li>Clear: es para limpiar la terminal.</li>
  <li>Man: sirve para ver un manual de los comandos.</li>
  <li>Sudo su: nos envía al usuario root que tiene permiso sin excepción para hacer cambios.</li>
  <li>Whoami: muestra el usuario en el que uno está conectado.</li>
  <li>More: se le agrega a un comando para ver las línea paginadas y no todo de una vez.</li>
  <li>Tail -n 10: se utiliza para ver las últimas 10 líneas.</li>
  <li>Head -n 10: se utiliza para ver las primeras 10 líneas.</li>
  <li>&&: permite correr un comando detrás del otro.</li>
  <li>Alias: permite crear una variable para correr comandos más rápido.</li>
  <li>Useradd: se utiliza para agregar usuarios.</li>
  	<ul>
      	<li>Useradd -p: para crearlo con un password.</li>
	</ul>	
  <li>History: se utiliza para ver todos los comandos que han sido utilizados recientemente.</li>
  <li>!!: corre el comando anterior. </li>
  <li>Dpgk -i: se utiliza para instalar un paquete.</li>
  </ul>
  <h3>Comandos Swap</h3>
   	<ul>
  	<li>for file in /proc/*/status ; do awk '/VmSwap|Name/{printf $2 " " $3}END{ print ""}' $file; done | sort -k 2 -n -r | less: nos da cuales procesos estan corriendo en el swap de momento.</li>
  	<li>free -h: muestra el espacio que utiliza en el swap. </li>
  	<li>Swapon: muestra un file con el espacio de swap</li>
  	<li>cat /proc/sys/vm/swappiness: porcentaje de memoria que utilizará para un swap. </li>
	</ul>
  <h3>Comandos para Montar un disco RAM</h3>
  	<ul>
  	<li>sudo mkdir /mnt/ram_disk: crea la carpeta para el disco de ram.</li>
  	<li>sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk: montar la memoria ram dentro de la carpeta creada.</li>
  	<li>Df -h / muestra los disco duros actuales en la computadora. Unidades montados en la computadora</li>
  	</ul>		
