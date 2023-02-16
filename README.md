# git 
* Git es un sistema de control de versiones, un software que sirve básicamente para getionar las versiones por las que va pasando el código de los proyectos.

* Si esta instalado tedrás un mensaje con la versión disponible en tu sistema

```bash
git --version
```
# Configuración inicial de Git

* comandos:
```bash
git config --global user.name "user.name"
git config --global user.email "user.email"
```
# Crear un repositorio Git
* Para crear un repositorio Git desde cero, debemos partir de una carpeta vacía. Estando situados en ella con el terminal de línea de comandos, se tiene que lanzar el comando:
```bash
git init
```
# Clonado de un repositorio Git
* Cuando queremos trabajar sobre un proyecto que ya ha sido iniciado por otras personas, o por nosotros mismos pero lo queremos obtener desde otro ordenador o servidor, la operación que tendremos que realizar es el clonado.
```bash
git clone https://github.com/usuario/nombre_repo.git
```
# Cómo hacer un commit
* Para poder hacer un commit sobre un repositorio primero debemos haber iniciado el respositorio con git init o bien haber clonado un repositorio remoto con git clone.
```bash
git add 'nameArchivo'
```
* Una vez han sido añadidos hacemos el commit, con un comando que generalmente tiene esta forma:

```bash
git commit -m 'Mensaje de la confirmación'
```
* modo main
```bash
git branch -M main
```
* Origen de mi repositorio 
```bash
git remote add origin https://github.com/YonatanLLa/Git.git
```
* Push
```bash
git push -u origin main
```