# Bitacora-de-Comandos
Parametros Generales:
  Sudo: da permiso de administrador a un comando.
  Apt: paquete que permite instalar software.
  Update: busca actualizaciones disponibles
  Upgrade: ejectua las actualizaciones encontradas (si hay).
  
Comandos Generales:
  ls: muestra carpetas dentro de un directorio.
      Algunos parametros
      ls -la: muestra los archivos ocultos
      ls -l: muestra las carpetas con mas detalles y en el formato de lista. 
      ls (nombre de carpeta): muestra los contenidos dentro del nombre de la carpeta
  mkdir: se utiliza para crear una carpeta
  Cd: se utiliza para cambiar de directorio
      Algunos parametros
      cd ~ o cd.. : se utliza para volver al directorio home o devolverse de directorio. 
      cd (nombre de carpeta): pasa al directorio de esa carpeta.
  touch: crea archivos
      Ejemplo
      touch archivo1.txt: crear un archivo de formato .txt llamado archivo1
  Cat: Muestra el contenido de un archivo. 
  Ps -aux: muestra todos los procesos que están corriendo de momento en el equipo
  Pstree: muestra los procesos pero con grafica de arbol donde se ven las jerarquias de los procesos. 
  |: se usa para juntar dos comandos. 
  grep: busca líneas con un parámetro específico.
      Ejemplo
      ls | grep archivo1.txt: en lista los archivos en el directorio que se incluyan en su nombre archivo1.txt
  kill -9: elimina o detiene un proceso
  
