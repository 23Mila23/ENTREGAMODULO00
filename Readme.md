# Aquí irán los pasos de la entrega Módulo 00:
1. Abro terminal y navego utilizando los comandos "cd" y "ls" hasta llegar a la carpeta BOOTCAMP. Pongo el comando code . para abrir Visual Studio Code
2. Open Folder - ENTREGAMODULO00
3. Abro la terminal en Visual Studio Code e ingreso el comando "git init"
4. Voy a GitHub y creo un nuevo repositorio con el mismo nombre. Copio la URL con SSH.
5. Conecto el repositorio de GitHub con el local con el comando git remote add origin URL
6. Compruebo conexión con git remote -v
7. New File -> Readme.md
8. Git Add .
9. Git commit -m "Readme del módulo 00"
10. Indico la rama de trabajo y hago push con git push --set-upstream origin master
11.Se refleja en GitHUB
12. Creo rama con git branch development y me cambio a esa rama con git checkout development
12. Modifico Readme añadiendo nuevos pasos
13. Git Add . + Git commit -m "Actualización 1 Readme" + git push --set-upstream origin development
14. Git checkout master para cambiarme a la rama master.
15. Git merge development master para mergear ambas ramas y actualizar la master con el contenido de development.
16. Git push
17.Actualizo Readme de nuevo con últimos pasos + git commit -am "Actualización 2 Readme"+ push desde la rama master.