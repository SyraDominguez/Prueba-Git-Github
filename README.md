# Prueba-Git-Github
Aprendiendo GIt y Github 101

## PRIMEROS PASOS PARA INICIAR UN REPO
1º. Crear carpeta en Working Area
2º. Crear archivo README.md
  - A través de Github
  - A través de la terminal con `echo "# Repositorio-de-Prueba-Diciembre" >> README.md`
3º. Crear Repositorio en Github - `git init`
4º Añadir el primer archivo README.md - `git add README.md`
5º Hacer Commit de Inicializacion - `git commit -m "Inicializando el Repo"`
6º Añadir repositorio remoto `origin` a repositorio local `main`- `git remote add origin https://github.com/SyraDominguez/Prueba-Git-Github.git`
7º Descargar todos (.) los cambios del repositorio remoto origin y fusionarlos con los cambios locales - `git pull .`
8º Empujar cambios de la rama `main` del repositorio remoto `origin` - `git push -u origin main` ( El argumento -u significa que establecerá una relación de seguimiento entre la rama local main y la rama remota main. Esto evitará que recibas el error "There is no tracking information for the current branch" en el futuro.)

## COMANDOS BASICOS 
