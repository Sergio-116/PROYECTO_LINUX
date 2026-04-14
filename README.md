# PROYECTO LINUX



## 🚀 PROYECTO LINUX - COMANDOS BÁSICOS



<p align="center">

&#x20; <img src="https://img.shields.io/badge/Linux-Terminal-black?style=for-the-badge\&logo=linux">

&#x20; <img src="https://img.shields.io/badge/Bash-Scripting-green?style=for-the-badge\&logo=gnubash">

&#x20; <img src="https://img.shields.io/badge/GitHub-Portfolio-blue?style=for-the-badge\&logo=github">

</p>



\---



### 📌 Descripción



Proyecto práctico enfocado en el uso de comandos Linux para la gestión de archivos, procesos y automatización desde terminal con los comando más usados.



\---


🧭 Navegación e historial
---



###### 📌 Paso 1 - History


Este comando se ejecuta para evidenciar los pasos que se han realizado en la terminal de Linux.

![Paso 1](https://raw.githubusercontent.com/Sergio-116/PROYECTO_LINUX/main/IMAGENES/01_History.png)


---



##### 📂 Gestión de archivos

En la gestión de archivos se puede relacionar todo los comando de reconocer donde está, listar los archivos creados, visualizar el contenido, buscar archivos, dar gestión de los mismo elaborando backups, editar, eliminar, entre otras funciones que se va a están nombrando en el transcurso del tema.

Inicialmente se realiza le creación de las carpetas utilizando el comando **mkdir nombre_de_la_carpeta** que en este caso se asigno el nombre como Practica_Linux, en seguida se utiliza el comando **cd Practica_Linux** para poder acceder a la carpeta, en cualquier caso de haber escogido otro nombre, debe ser mencionado en después de **cd**. 

Es importante reconocer hay dentro de cada carpeta, que archivos o elementos hay, en el lugar que este ubicado, para ello, se utiliza el comando **ls -l**, como se evidencia en la siguiente imagen.

![Paso 2](https://github.com/Sergio-116/PROYECTO_LINUX/blob/f34cd6e64894879cd176013e319eaaf4a492f979/IMAGENES/02_ArchivoLogs.png)

En la gestión de archivos también se puede necesitar encontrar un archivo dentro de una carpeta, tenga en cuenta que solo buscara en dicha carpeta donde este ubicado, sea el caso de tener una carpeta dentro en la que usted se encuentra, no va a buscar, el comando para realizar esta búsqueda es **find _El nombre del archivo junto con la extención_**. 

Es menester hablar de como retroceder a la carpeta anterior, crear nuevo archivo vacio, es decir sin nada de contenido, en los comando utilizados son **cd ..* y **touch nombre del archivo*

![Paso 3](https://github.com/Sergio-116/PROYECTO_LINUX/blob/f34cd6e64894879cd176013e319eaaf4a492f979/IMAGENES/03_UsoNano.png)

Guardar un respaldo es tan importante como desarrollar en cualquier ámbito, por tal razón, **cp combre del archivo ../Carpeta a donde quiere hacer backup/**, en este caso se realizo una carpeta adentro de la carpeta Practica_Linux en la misma gerarquia de la carpeta Documentos, de este modo se realizo el Backup. 

![Paso 4](https://github.com/Sergio-116/PROYECTO_LINUX/blob/f34cd6e64894879cd176013e319eaaf4a492f979/IMAGENES/04_RealizacionBackup.png)


En su momento todo debemos realizar un cambio de nombre a algún archivo, el comando utilizado en Linux **mv nombre_inicial nombre_final** se evidencia en la siguiente imagen

![Paso 5](https://github.com/Sergio-116/PROYECTO_LINUX/blob/f34cd6e64894879cd176013e319eaaf4a492f979/IMAGENES/05_Cambiar_nombre.png)

Para eliminar un documento o carpeta hay dos maneras de llevar a cabo **rmdir nombre** y **rm -r nombre ** de la segunda manera se elimina aquello que se halla seleccionado

![Paso 6](https://github.com/Sergio-116/PROYECTO_LINUX/blob/f34cd6e64894879cd176013e319eaaf4a492f979/IMAGENES/06_ConfiguacionPermisos.png)


La edición de un archivo es de mucho cuidado por tal razón es necesario brindar los permisos requeridos de acuerdo a lo que se requiera, de tal modo el comando usado es **chmod 600 nombre del archivo** para diferenciar analizar la siguiente imagen 

![Paso 7](https://github.com/Sergio-116/PROYECTO_LINUX/blob/f34cd6e64894879cd176013e319eaaf4a492f979/IMAGENES/07_VerProcesos.png)
 

##### ⚙️ Procesos

El comando **TOP** se utiliza para visualizar los proceso internos de la maquina en ejemplo se muestra en la siguiente imagen

![Paso 8](https://github.com/Sergio-116/PROYECTO_LINUX/blob/cf7960889f7e67b5ca97f4d57c59e03da2db9821/IMAGENES/09_UsoTOP.png)
 

Para matar el proceso se utiliza el comando **kill PID del proceso que quiere finalizar** es decir KILL 564, para poder salir de este proceso se debe oprimir la letra **q**

![Paso 9](https://github.com/Sergio-116/PROYECTO_LINUX/blob/f34cd6e64894879cd176013e319eaaf4a492f979/IMAGENES/08_MatarProcesos.png)


\---



##### 🧪 Script Final



###### 📌 Paso 10 - Archivo Mis Comandos


![Paso 10](https://github.com/Sergio-116/PROYECTO_LINUX/blob/cf7960889f7e67b5ca97f4d57c59e03da2db9821/IMAGENES/10_ArchivoMisComandos.png)




###### 📌 Paso 11 - Evidencia Script


![Paso 11](https://github.com/Sergio-116/PROYECTO_LINUX/blob/cf7960889f7e67b5ca97f4d57c59e03da2db9821/IMAGENES/11_EvidenciaScrip.png
)




\---



##### 💡 Tecnologías



\- Linux 🐧  

\- Bash  

\- Git \& GitHub  



\---



\## 👨‍💻 Autor



\*\*Sergio Quintana\*\*

