### Titulo
# Titulo mas grande
###### Titulo mas pequeño
1. Aprender  md
2. Aprender terminal
3. Esto es una lista ordenada

```python
a = 3
def fun (a):
    return a
```
* Lista desordenada

## Comandos terminal
### Listar los ficheros de la carpeta donde estamos
```bash
1. ls
2. clear
```
* No reciben argumentos
```bash
1. ls -a
```
* Los puntos indican el directorio en el que estamos y uno más arriba.
```bash
1. ls git_practice -a
2. ls -a git_practice
```
* Esto es lo mismo, da igual el orden
* Normalmente a ls le pasaremos un directorio que tiene cosas que queremos listar, podemos pasarle un fichero concreto como notes.md, nos devuelve notes.md pero no nos es muy útil.
* Para autocompletar, escribimos los primeros caracteres y le damos al tabulador
```bash
1. pwd
```
* Significa print working directory, nos indica la ruta absoluta y donde me encuentro
```bash
1. --help ls
```
* Man es de manual, nos da información.
```bash
1. cd carpeta_nueva
```
* Significa change directory, y recibe un argumento, que es a la carpeta a la que nos queremos mover.
```bash
1. cd ..
```
* Vamos a volver a la carpeta anterior, subimos a un nivel superior.
```bash
1. rm file.py
```
* Para eliminar un fichero
* El scripting es para crear ejecutables de terminal
* Para eliminar carpetas debemos mirar si tienen ficheros dentro. Si le hacemos un ls o un ls -a y no nos devuelve nada, está vacía. 
```bash
1. rmdir carpeta
```
* Esto elimina la carpeta, para crear una nueva: make directory
```bash
1. mkdir nombrecarpeta
```
* Ahora vamos a crear ficheros. Lo bueno de hacerlo desde terminal, es que tenemos pleno control sobre la extensión del mismo: touch nombre_fichero.extensión
```bash
touch newfile.txt
```
*Para eliminar una carpeta que tiene ficheros dentro tenemos que hacerlo de forma recursiva, haremos la operación reiteradas veces, la misma operación se ejecuta a sí misma. 
* Eliminaremos los ficheros de la carpeta de forma recursiva hasta que no queden más y entonces eliminará también la carpeta
```bash
rm carpeta -r
```
*Ahora veremos cómo crear un fichero dentro de una carpeta en la que no estamos.
*pwd nos imprime la ruta absoluta de donde nos encontramos, significa print working directory
*Para diferenciarla de una ruta relativa. Siempre que la impresión empiece con una diagonal, es una ruta absoluta. En windows puede aparecen como c:barra barra, pero bueno. 
*Crear un fichero aqui
```bash
touch ./fichero.txt
```
* Lo mismo si escribo toda la ruta donde escribirlo
```bash
touch /g/Mainpython1/git_practice/fichero.txt
```
*En una carpeta concreta
```bash
touch ./carpetanueva/fichero.txt
```
*Esto nos sirve para niveles superiores o para niveles inferiores.
*Podemos hacer ls -l de un fichero para saber quien tiene el control del fichero.
*r nos dice read, w nos dice write. Nos indica los niveles de acceso por tripletes. El superuser, el acceso a grupos, y el acceso individual.
*Pero por lo general, no hacemos ls de un file, sino que hacemos un cat del fichero.
```bash
cat fichero.txt
```
*global regex print o algo así, grep nos sirve para capturar alguna palabra o una linea en un texto en un archivo
```bash
cat fichero.txt | grep loquequierocapturar
```
*Para modificar un fichero directamente desde la terminal:
```bash
nano fichero.txt
```
* Para mover los ficheros:
```bash
mv fichero.txt./carpetadondeloquieromover
```
* Para cambiar el nombre
```bash
mv nombredelarchivoantiguo.txt nombrenuevo.txt
```
* Esto tambien sirve para carpetas.
* Para crear ficheros ocultos tengo que ponerle el prefijo al nombre del fichero : .
* Así podremos verlo solo cuando hacemos ls -a, y no cuando hacemos ls.
```bash
1. code . 
```
* Le decimos que nos abra visual studio code en la carpeta en la que estamos





