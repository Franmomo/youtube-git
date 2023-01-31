# Comandos útiles de GIT:

01. git init ==> inicializa y crea la carpeta git en nuestro directorio.
02. git add . ==> toma todos los archivos desde el git init o desde el ultimo commit y los prepara para una fotografía
03. git reset . ==> revierte todo lo que haya realizado el git add .
04. git commit ==> realiza la fotografía de los archivos añadidos anteriormente
05. git checkout --. ==> reconstruye todo lo del ultimo commit. 
06. git log ==> muestra el log de las acciones realizadas
07. git commit -- amend ==> arregla el ultimo commit ejecutado
08. git checkout -b (crea una rama) rama-heroes   (nunca trabajar en la rama MASTER !!!) 
09. git branch ==> muestra las ramas actuales
10. git checkout master ==> pasa a la rama master
11. git branch -d rama-heroes => borrar una rama 
12. ==> desplegar a un repositorio externo:
    git remote add origin https://github.com/Franmomo/youtube-git.git
    git branch -M main
    git push -u origin main
13. git push ==> para subir actualizaciones sobre un proyecto ya cargado.    
14. git commit -am "" ==> para realizar a la vez los comandos git add . + git commit -m ""

