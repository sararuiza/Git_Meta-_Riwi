.md, es un formato para documentacion 
#Configuracion 

comando para conocer la version que tenemos de git:
-  git -v
- git --version

comandos para configurar git por primera vez:
-  git config --global user.name "your name"
-  git config --global user.email "your email"

comando para ver que usuario esta configurado o el correo electronico:
- git config --global user.name
- git config --global user.email
- git config --list


comando para inicializar git en un directorio(prenderlo por cada carpeta que vaya a versionar):
- git init

pasos para crear una version de mi codigo:
1. agregar los cambios:
- git add . (para agregar TODOS los archivos)
- git add *.js(si quiero agregar todos los archivos .js)
- git add *.html(agregar todos los archivos html)
- git add nombre-del-archivo(para un archivo especifico)

comandos para ver el estado de los archicos:
- git status

comando para crear una version en git o comprometer los archivos:
- git commit -m "descripcion del commit"

versiones que se tienen hasta el momento de un proyecto:
- git log --oneline
- git log (para ver las versiones con mas detalles; quien lo hizo, como lo hizo, desde donde, fecha)

navegar entre versiones:
- git checkout "id-la-version" este comando solo funciona de anera local 

para devolverme a la ultima version:
- git checkout (master o main)

comando para volver a la enterior version:
- git checkout-- .









