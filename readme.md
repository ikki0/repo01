Hola, en este documento deberé de documentar todos los pasos que voy haciendo para crear un repositorios.

1. Crear fichero llamado readme.md
2. Utilizar el comando git add readme.md para mover el fichero al staging area
3. Utilizar el comando git commit -m "mensaje del commit" para 'lanzar' todos los ficheros del staging area al repositorio local
4. En github.com seleccionamos el botón con forma de + y hacemos click en 'nuevo repositorio'
5. Escribimos un nombre para el repositorio, lo mantenemos en públicmo y hacemos click en crear nuevo repositorio
6. Dentro de la consola del editorio copiamos línea por línea los siguientes comandos:
   1. git remote add origin git@github.com:ikki0/repo01.git
   2. git branch -M main
   3. git push -u origin main
7. Por último hacemos un git commit -am y ya deberíamos ver los cambios en el repositorio remoto.
