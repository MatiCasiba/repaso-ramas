# Clase 06 -  Bootcamp

## Repaso GIT

## creo el repositorio git

```sh
git init
```
# Listo el estado de los archivos

```sh
git status
```

# Haciendo un coommit
1. Agrego al area de stagin, los archivos que necesito que formen parte del commit

```sh
git add <nombre-arcivo>
git add <nombre-archivo> <nombre-archivo> <nombre-archivo>
git add . #Agrega todos los archivos que tengo en el workin directory (md)
```

2. Hago el commit

```sh
git commit -m "Mensaje descriptivo"
```

# Cambiar el editor por nano

```sh
git config --global core.editor nano
git config --global core.editor "code -wait"
```
# Ver listado de commits que hice en el repo

```sh
git log #version larga
git log --oneline #version corta
```

# Agregrar un remoto a mi repositorio local

```sh
git remtoe add origin <url-al-repo-remoto>
git remote add origin https://github.com/MatiCasiba/repaso-ramas.git
```

# Para ver sis e agrego el repo remoto

```sh
git remote -v
```

# Subo al remoto el repositorio local

```sh
git push -u origin main # La primera vez
git push
```

