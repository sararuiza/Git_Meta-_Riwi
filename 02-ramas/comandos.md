RAMAS 
las ramas son individuales, es una copia y todo lo que se haga en la rama no afecta la main o el proyecto principal, las ramas son independientes, es facil combinarles, es eficiente

MERGE
un merge es una la union enre mi rama y el tronco principal. el merge es el proceso de integrar los cambios, se une el codigo y el historial de versiones

CONFLICTO
es cuando dos personas tocan una misma linea de cogigo y luego intentan fusionar las ramas con marge

# Comando para listar las ramas
- git branch (nos permite ver todas las ramas disponibles en el proyecto)

# comando para crear una nueva rama
- git branch nombre_rama(sin espacios)

# comando para cambiar de rama
- git checkout nombre_rama
- git switched nombre_rama

# comando para elimanar una rama
- git branch -D nombre_rama

# cambiar entre ramas
- git switch nombre_rama
- git checkout nombre_rama
- git chechkout -b nombre_rama

# desvincular un archivo de git que se le estaba dando segumiento
- git rm --cached nombre_archivo

# comando para crear una nueva version con archivos que ya se estaban dando seguimiento
- git commit -am nombre_rama

# comando para unir ramas
- git merge nombre_rama

# como crear un alias o un shortwords
- git config --global alias.lg `escribo el comando a ejecutar`