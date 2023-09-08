Hola, en este documento deberé de documentar todos los pasos que voy haciendo para crear un repositorios.

1. Crear fichero llamado readme.md
2. Utilizar el comando git add readme.md para mover el fichero al staging area
3. Utilizar el comando git commit -m "mensaje del commit" para 'lanzar' todos los ficheros del staging area al repositorio local
4. Si a continuación utilizamos el git push observaremos que no se puede envíar los cambios del repositorio local al repositorio remoto porque aún no hemos definido/creado el repositorio remoto.
5. Si utilizamos el comando git remote -v observaremos que no aprece nada, eso es porque aún no tenemos ninguna conexión entre el repositorio local y el repositorio remoto
6. Para crear el repositorio remoto en github.com seleccionamos el botón con forma de + y hacemos click en 'nuevo repositorio'
7. Escribimos un nombre para el repositorio, lo mantenemos en público y hacemos click en crear nuevo repositorio
8. Dentro de la consola del editorio copiamos línea por línea los siguientes comandos:
   1. git remote add origin git@github.com:miUsuario/repo01.git
   2. git branch -M main
   3. git push -u origin main
9. Si a continuación hacemos un git remote -v observaremos que ahora sí existe nuestro repositorio remoto con el nombre que lo hemos creado.
10. hacemos un git commit -am
11. Por último hacemos un git push para lanzar los cambios del repositorio local al repositorio remoto y por tanto deberíamos de ver estos cambios en el repositorio remoto de github.

![No ser cargo correctamente la imagen](./img/Captura%20desde%202023-09-08%2012-20-35.png "Imagen de git con los cambios en readme")
