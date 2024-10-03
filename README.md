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
