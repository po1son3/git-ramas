# GIT RAMAS (BRANCHES)
## Crear un repositorio
````sh
git init
````
## Ver el status de los archivos
`````sh
git status
`````
## Git ALIAS 
````sh
git config --global alias.st "status" --short
git config --global alias.a "add"
git config --global alias.c "commit -m"
git config --global alias.l "log --oneline"
````
## Ver las diferencias entre el WD y LR
````sh
git diff
````

## VER COMMITS
````sh
git show <numero hash>
````

## Crear una RAMAS
```sh
git branch <nombre-rama> # Crear una ramaa y nos deja en la rama original
git switch -c <nombre-rama> # Crea una rama y nos mueve a la rama que se creo
```
## Me muevo entre RAMAS
````sh
git switch <nombre-rama>
git switch feature/ramas #ejemplo
````
## Comparar entre los últimos commits de las ramas
````sh
git diff <nombre-rama-que-quiero-comparar> # Comparo la rama actual contra la rama que indico
git diff dev # ejemplo. comparo feature/ramas con dev
````
## Ver las ramas locales y remotas 
````sh
git branch -a # me muestra las ramas locales y remotas
````
