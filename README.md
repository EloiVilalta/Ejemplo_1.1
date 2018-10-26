# Ejemplo_1.1
Pasos realizados para el ejercicio 1.1

# Primer Terminal
  Lo que hemos hecho para crear este archivo (Contenido añadido desde la web github)

Creamos carpeta y cambiamos a esa carpeta  
`$ mkdir ejemplo && cd ejemplo`  
creamos un archivo de texto vacío  
`$ touch prueva.txt`  
Inicializamos un GIT en esa carpeta  
`$ git init`  
Vemos que hay el fichero prueva.txt pero en naranja, lo que significa que no se está haciendo control de versiones  
`$ git status`  
Añadimos este fichero al control de versiones  
`$ git add prueva.txt`  
Aparece en verde, significa que no está añadido al repositorio  
`$ git status`  
Creamos el repositorio en GITHUB desde el terminal  
`$ git remote add origin https://github.com/EloiVilalta/Ejemplo_1.1.git`  
Subimos el fichero prueba.txt al repo remoto (GITHUB), usando -u la primera vez  
`$ git push -u origin master`  
  
Vemos como en la web aparece el fichero  
  
  
  
# Segundo Terminal  
Pasos realizados para crear este segundo archivo (contenido añadido desde la web Github)  
  
Creamos segunda carpeta para trabajar como si fuera otra maquina  
`$ mkdir Cloneejemplos &&cd Cloneejemplos`  
Clonamos el repositorio original en esta otra carpeta  
`$ git clone https://github.com/EloiVilalta/Ejemplo_1.1.git`  
nos vamos a la carpeta del repositorio descargado  
`$ cd Ejemplo_1.1`  
Vemos que no hay ningun cambio pendiente de añadir o de hacer commit  
`$ git status`  
Vemos que hay el archivo prueva.txt del original  
`$ ls`  
Creamos un segundo fichero  
`$ touch prueva2ndoTerminal.txt`  
Vemos que hay que añadir este fichero  
`$ git status`  
Lo añadimos  
`$ git add prueva2ndoTerminal.txt`  
Vemos que tenemos archivos pendientes de commit  
`$ git status`  
Hacemos el commit en mi base de datos local  
`$ git commit -m "Este es un segundo fichero creado por 2ndo terminal"`  
Subimos al repo remoto (GITHUB), ojo que no he usado -u esta vez, y lo suvimos del LOCAL al REMOTO  
`$ git push origin master`  
  
Vemos como en la web aparecen los dos ficheros  
  
