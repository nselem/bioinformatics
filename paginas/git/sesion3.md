# Sesión 3  
¡Buenos días ! Empezemos por poner nuestro nombre completo en el documento colaborativo.  
  
## Repaso  
En esta sesión vamos a repasar google drive y grep y después crearemos nuestro repositorio de github.  

### Ejemplos de repaso    
  -Ejemplo for. Vamos a leer una lista de sus nombres y voy a crear carpetas con ellos que les compartiré en el drive.  
  -Ejemplo script. Este for lo voy a poner en un script.    
  `for line in $(cat $1|cut -d' ' -f1) ; do mkdir date-$line; done`  
lista  
> Nelly Selem  
> Abraham Avelar  
> Manu Vi  
  -Ejemplo grep Las secuencias que no contienen ACGT. Aqui puedes consultar [expresiones regulares](https://v4.software-carpentry.org/regexp/index.html).     
  -Ejemplo perl one liner Cambiar dueño Araceli por Bety  
 
### Ejercicios de repaso    
1. Haz un google doc describiendo tu proyecto (max 5 líneas) y compartelo en el documento colaborativo.  
2. Agenda en tu calendario el 5 de octubre como día de presentación de tu proyecto.    
3. En tus tareas de hoy coloca Ejercicios de drive, Aprender Github, Aprender markdown.   
4. Crea una presentación de google drive para tu proyecto y comparte el link en el documento colaborativo.  
5. Cambia de color tu carpeta.  
6. Mueve tu google doc y tu presentación a tu carpeta.  

El control de versiones puede empezar desde el google drive. Veamos un ejemplo.  

### Ejercicio  
Haz un script que mediante un ciclo for cree carpetas para sus estudiantes en el laboratorio. Cada carpeta debe contener un archivo vacío llamado Protocolo-estudiante. Sugerencia googlea el comando `touch` a ver qué hace. Coloca tu solución en el documento colaborativo. Puedes trabajar con un compañero. Sube tu carpeta a tu drive.         

## Control de versiones con git  
### Git y Github  
Esta parte de la sesión está basada en la [lección de git software carpentry](https://swcarpentry.github.io/git-novice-es/)  
### Gitpages
En settings ir a GitHub pages  
https://swcarpentry.github.io/git-novice-es/ 
En source seleccionar master branch. Ir a master branch. En tema seleccionar alguno

### Ejercicio 
1. Crea un repositorio LaboratorioNum en tu cuenta de GitHub.  
1. Haz un readme de tu repositorio.
2. En tu carpeta git utiliza `git clone direcciondeturepositorio`
3. Modifica tu readme subiendo una foto. ¿Cómo se hace esto en mark down?    
4. Haz pull de tu repositorio, ¿que pasa?  
5. Sube tu script a este repositorio de github, usando add, commit, push.  


## Tarea  
Agrega a tu google sites una página con tu github y una página con tus carpetas de los protocolos de tus estudiantes.   
