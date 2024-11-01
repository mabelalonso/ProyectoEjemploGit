# Tarea 1: Introduccion a Git

## Objetivo del programa
Repasar los comandos básicos de Git y crear un repositorio en GitHub.

## Descripcion del programa
Es una aplicación sencilla en Java para imprimir un mensaje ("Hola, GIT") en la consola.

## Instrucciones para poder ejecutar el programa HolaMundo.java
1. **Preparar el archivo**
Abrir en el editor de texto preferido y copiar el codigo.
2. **Guardar el archivo** 
Salva el archivo con el nombre *HolaMundo.java*. Verifica que contenga la extension *.java* y que el nombre de la clase coincida con el nombre del archivo.
3. **Terminal**
Abrir una terminal o lista de comandos.
4. **Directorio del archivo**
Ubicarse en el directorio donde esta guardado el archivo *HolaMundo.java*. Para cambiar de directorio utiliza cd. *Ejemplo: cd ruta/al/directorio*
5. **Compilar el archivo**
Para compilar el archivo utilizar el siguiente comando: *javac HolaMundo.java*
6. **Ejecutar el programa**
Uilizar el siguiente comando: *java HolaMundo*
7. **Salida en la terminal**
En la terminal se debe poder visualizar la siguiente linea: *"Hola, GIT"*

## Comandos utilizados
+ git config --global user.name "Nombre Usuario"
+ git config --global user.email "userEmail@correo.com"
+ cd "C:\user\nombre\ruta-de-la-carpeta\carpeta"
+ ls -al
+ git init
+ git remote add origin url-en-gitHub-del-repositorio-remoto
+ git remote -v
+ touch .gitignore
+ git -A
+ git commit -m "mensaje del commit"
+ git push origin master
+ git status
+ git push

## Notas sobre el archivo .gitignore
Se crea para indicarle a Git que archivos o directorios debe ignorar.
Y en este proyecto solo se ignora el archivo *debug.log*.

## Descripcion de lo que muestra el programa al ejecutarlo
Al ejecutar el programa *HolaMundo.java* debe aparecer en la terminal el mensaje "Hola, GIT". 

## Como verificar que debug.log no se subio
+ Dentro del archivo *.gitignore* revisar que este escrita la siguiente linea "/debug.log".
+ Utilizar en la terminal (Git bash) el comando *git status* y revisar que el archivo no este siendo rastreado por Git.
+ Ir a la pagina de GitHub, seleccionar el repositorio, navegar por el arbol de archivos y revisar que no se encuentre el archivo.