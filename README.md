#COMANDOS UTILIES EN GIT

#PARA CONFIGURAR EL USUARIO Y EL CORREO
0. git config --global user.name "mavalenzz"
git config --global user.email "alejandra.valenzuela0125@jala.university"

#INICIALIZAR GIT
1. git init

#PARA PREPARAR PARA CREAR UN SNAPSHOT
2. git add . #cambia de U a A

#PARA REVERTIR EL (2)
3. git reset . #cambia de A a U

#PARA CREAR UN COMMIT
4. git commit -m "Nombre"

#PARA RESTAURAR LOS CAMBIOS REALIZADOS
5. git checkout -- .

#LISTADO DE TODOS LOS COMMITS
6. git log (q para salir)

#PARA ARREGLAR EL NOMBRE DEL ULTIMO COMMIT
7. git commit --amend
presiona i para aniadir nuevos textos
para salir pon escape :wq!
no me funciono xd mejor control + o, enter y control + x

#PARA CREAR RAMAS PARA TRABAJOS COLABORATIVOS
8. git checkout -b nombre #b significa branch

#PARA VER LAS RAMAS QUE SE ESTAN CREANDO
9. git branch

#COMO PARA QUE NOS CENTREMOS EN LA RAMA MASTER
10. git checkout master

#SI QUEREMOS COMBINAR AMBAS RAMAS 
11. git merge nombre_rama

#PARA BORRAR UNA RAMA
12. git branch -d nombre_rama

#PARA VINCULAR CON GIT HUB,
13. crea un repositorio, luego aniade estos comandos 

    git remote add origin https://github.com/mavalenzz/youtube-git.git
    git branch -M main
    git push -u origin main

    capaz te pida alguna autorizacion

#PARA SUBIR AL REPOSITORIO DE GIT HUB
14. git push