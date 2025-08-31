# Aprendiendo git
## Aprendiendo git
### Aprendiendo git
#### Aprendiendo git
##### Aprendiendo git
###### Aprendiendo git


# Comandos iniciales de git

```bash
git init 
```
## Crear un nuevo reporsitorio remoto
```    
git remote add origin url_repositorio_remoto
```
## Nueva modificacion
```
git add .
git commit -m "mensaje"
git push origin master
```


# Hacer pull request 
## Paso 1. Hacer un fork del repo

-Ir al repo original  fullstack-bases-git
-clic a Fork.

-Ahora tendremos una copia en mi cuenta (https://github.com/TU-USUARIO/fullstack-bases-git).

```
 git clone https://github.com/Perez8899/fullstack-bases-git.git

 cd fullstack-bases-git
 ```

 ## craer nueva rama
 ```
git checkout -b fix/html-update
 ```

## Se hace lo modificacion
```
git add index.html
git commit -m "Mensaje"
```

## Subir la rama a github
```
git push -u origin fix/html-update
```
```
fix/ → es un prefijo que usamos por convención para indicar el tipo de cambio:

           fix/ → cuando corriges algo.

           feature/ → cuando agregas una nueva funcionalidad.

           docs/ → cuando solo cambias documentación.

           hotfix/ → arreglos urgentes.

html-update → es el nombre descriptivo de tu cambio
```
## Crear Pull Request
```
Ve a tu fork en GitHub (https://github.com/TU-USUARIO/fullstack-bases-git).

Botón amarillo: Compare & pull request → dale clic.

Verificar 
       compare branch: fix/html-update

Descripcion

Clic en Create pull request
```

# ramas
```
ver  ramas git branch

git branch hperez
```
# Cambiar de rama
```
git checkout -b hperez

y agregamos los cambios git add .  git commit....
```

   # Subir la rama
   ```
   git push origen hperez
   ```
## se hace pull request y se hace el merge
### los cambios se hiso en la rama hperez...
#### para que en la rama master aparescan los cambios se hace  pull
```
git pull origin master
```

## o para tyraer los cambios de otra rama
### estoy en rama master, 
```
tonses hago-  git merge hperez

```