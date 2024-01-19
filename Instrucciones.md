# Git
## Comandos para la recuperacion de versiones
```
git branch Nombre_Rama
```
Permite crear ramas y si no se coloca un nombre permite ver las ramas creadas
```
git cheackout Nombre_Rama
```
Permite cambiar ramas

```
git merge Nombre_Rama
```
Fusionar ramas 
```
git cheackout ID_Log Nombre_Archivo
```
Mostrara como se encontraban los archivos en cierta version , y generara una nueva rama temporal
```
git reset --hard ID_Log
```
Recuperar una version anterior de la rama 
 
## Comandos para manejar los commit

###### Cambiar nombre


git commit --amend


## Comandos para manejo de github 
### Configurar proyecto 
Generar llave SSH
Insertar SSH en github 
Configurar origin 
```
git remote add origin clave SSH del proyecto
```
### Subir datos

git push origin master

### Descargar Datos

git pull origin master --allow-unrelated-histories