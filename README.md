# Activividades
## 1. Inicializacion de un repositorio GIT
**Objetivo**: Aprender a crear un repositorio Local.
**Instrucciones**:
1. Abrir una Terminal
2. Navegar a la carpeta del proyecto
```bash
cd mi_proyecto
```
3. Inicializar el repositorio GIT con el comando:
```bash
git init
```
4. Verificar el estado con:
```bash
git status
```
## 2. Realizar el primer commit
**Objetivo**: Realizar el primer commit local
**Instrucciones**:
1. Crear un archivo index.html o README.md
2. Agregar contenido a los archivos
3. Usa `git add` para agregar el archivo al area de preparación
4. Realizar un commit con el comando:
```bash
git commit -m "Mi primer commit"
```
5. Verificar el estado con:
```bash
git log
```
Para asegurarse que el commit se ha realizado correctamente.
## 3. Creacion y conexion a un repositorio GITHUB
**Objetivo**: Crear un repositorio remoto en github y vincular con el repositorio local
**Instrucciones**:
1. Crear una cuenta en github [GITHUB](https://github.com)
2. Crear un nuevo repositorio en github (sin inicializar el README.md)
3. En la terminal, agregar el repositorio remoto con el comando:
```bash
git remote add origin https://github.com/miusuario/mi_proyecto.git
```
4. Veirficar que se haya agregado correctamente con:
```bash
git remote -v
```
5. Subir el primer commit a GITHUB con:
```bash
git push origin master
```
## 4. Crear y trabajar con ramas
**Objetivo**: Aprender a crear y trabajar con ramas
**Instrucciones**:
1. Crear una nueva rama 'ramaDesarrollo'
```bash
git branch ramaDesarrollo
```
2. Cambiar a la 'ramaDesarollo' con:
```bash
git checkout ramaDesarrollo
```
3. Modifcar los archivos de desarrollo
4. Agregar y realizar un commit con los cambios realizados
```bash
git add .
git commit -m "Cambios en la rama desarrollo"
```
5. Volver a la rama master
```bash
git push origin master
```