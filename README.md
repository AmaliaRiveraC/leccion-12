# Instrucciones de comandos para GitHub

## El primer comando que utilizaremos en nuestra consola, después de haber creado nuestro nuevo repositorio en GitHub será

git init

###### Este comando inicializara la modificacion del repositorio

## Luego recurriremos al comando

git add .

###### Este comando
git add"
###### seguido de un
 .
###### subira toda la carpeta en la que estamos posicionados

###### Tambien podriamos poner

git add nameFile

##### este comando solo subira un archivo, el cual correponda con el nombre del archivo que queremo subir

## Continuaremos colocando el comando

git commit -m "Nombre de la version"

######Este comando servira para identificar la version que estamos subiendo, es por ello que debemos de ser muy descriptivos a la hora de nombrar nuestros "commit"

## Despues usaremos el comando

git remote add origin URL

## y para finalizar

git push -u origin master
