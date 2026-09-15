# Creación y sincronización de repositorios con Git y GitHub
#
Nombre completo: Jose Valentin Alvarez Reyes
Matrícula: 2630144
#
## Objetivo
Aprender a crear un repositorio local utilizando Git, vincularlo con un repositorio remoto en GitHub y comprobar la sincronización entre ambos.
#
## Descripción del procedimiento

Primero creamos una carpeta llamada "practica-git-nombre-apellido" en la ubicacion de su eleccion. Posteriormente inicializamoz el repositorio utilizando Git, con el comando `git init` y se estableció la rama principal con el nombre "main", con el comando `git brach -M main`.

Después crearemos los archivos "README.md" y "datos.txt" y en el archivo "datos.txt" colocaremos información relacionada con la práctica.

Posteriormente se agregaron los archivos al Staging Area, con el comando `git add .` y comprobaremos con el comando `git status`. Una vez comprobado realizaremos el primer commit, con el comando `git commit -m "mensaje"`. Después crearemos un repositorio público en GitHub con el nombre "practica-git-nombre-apellido", copiaremos la direccion "HTTPS" proporcionada por GitHub y lo vincularemos Git con GitHub con el comando `git remote add origin URL` desde PowerShell. Comprobaremos la conexion con el comado `git remote -v`.

Finalmente se realizaron pruebas de sincronización en ambas direcciones. Insertaremos el comando `git push -u origin main` para subir el repositorio a GitHub, Puedes comprobarlo desde tu repositorio en GitHub.

Ahora modificaremos nuestro "datos.txt" agregando un mensaje y crearemos nuestro commit desde GitHub presionando el boton en verde "Commit Changes".
Después descargaremos los cambios desde PowerShell, con el comando `git pull origin main`

Ya casi para finalizar abriremos nuetrso "datos.txt" desde nuestra computadora y escribiremos otra linea de texto. Revisaremos el estado del "datos.txt" con el comando `git status` y agregaremos el cambio al staging area, con el comando `git add .`. Para finalizar crearemos nuestro segundo commit y lo subiremos a GitHub con el comando `git push`
 
 Con eso ya hemos concluido nuestra sincronizacion local a GitHub y sincronizacion GitHub a local.
 #
## Comandos de Git utilizados
#
| Comando | Función |
|:-------:|:-------:|
| git init | Inicializa un nuevo repositorio Git en la carpeta actual. |
| git branch -M main | Establece el nombre de la rama principal como "main". |
| git status | Muestra el estado actual del repositorio. |
| git add . | Agrega los archivos modificados al Staging Area. |
| git commit -m "mensaje" | Guarda los cambios registrados en un nuevo commit. |
| git remote add origin URL | Vincula el repositorio local con un repositorio remoto. |
| git remote -v | Muestra los repositorios remotos configurados. |
| git push | Envía los commits del repositorio local hacia GitHub. |
| git pull origin main | Descarga los cambios de GitHub y los integra en el repositorio local. |
#
## Archivos del repositorio
### README.md
Este archivo contiene la documentación de la práctica, incluyendo el objetivo, procedimiento a segir, comandos utilizados y conclusión.

### datos.txt
Contiene información relacionada con la práctica y fue utilizado para comprobar la sincronización entre GitHub y el repositorio local.

### Historial de cambios
Durante la práctica se realizaron varios commits para registrar los cambios realizados en el repositorio.
#
## Conclusión
#
Al realizar esta practica aprendi a utilizar Git para administrar un repositorio local y a utilizar GitHub como repositorio remoto, también tuve mayor comprencion del Staging Area y de los commits para registrar los cambios realizados en un proyecto. Tambien pude aprender a sincronizar los archivos en ambas direcciones y a como enviar los cambios del repositorio local hacia GitHub y viceversa, gracias a esto podre mantener actualizado un proyecto y facilita el trabajo con sistemas de control de versiones.