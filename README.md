# prueba-rama
Modelo de prueba para corroborar y sacarme dudas con las ramas de Git & GitHub

//Crea una nueva rama: SOLO CREARLA, NO NOS MOVEMOS A ELLA
git branch nombreRama


//Muestra la rama en la que estamos parados:
git branch


//Nos movemos a una nueva rama:
git checkout nombreRama


Luego, para unir a la rama main con la rama que creamos, tenemos que estar parados en la main para ejecutar:
git merge nombreRama


ANTES QUE NADA
Hacer git fetch que mergea todo al remoto, para que todos los archivos estén en orden



// A la hora de hacer un merge (unir ramas), hacer un:
git merge origin/main
// Esto lo que hace es que envía toda la información del main a su rama, esto genera los conflictos en una rama DISTINTA a main


//Y luego, hacer un nuevo commit, que pase todos los datos, ya con el conflicto resuelto, a main 
//Para eso, hay que moverse a la main
git checkout origin/main

//  Y luego, estandos parados en main, traer los archivos de la rama Pablo
git merge nombreRama

ES IMPORTANTE CORROBORAR SIEMPRE EL git status


TIPS:
// Compila los archivos, hay que tener en cuenta en dónde deseas que compile esos archivos
merge 

// Muestra y crea ramas
branch 

// Sirve para moverse entre ramas
checkout 