
# Práctica 03: Permisos y usuarios en Linux

## Objetivo

Comprender cómo se gestionan los usuarios, los grupos y los permisos de archivos y directorios en Linux.

## Conceptos básicos

- **Usuario:** cuenta que permite utilizar el sistema.
- **Grupo:** conjunto de usuarios que pueden compartir permisos.
- **Lectura (r):** permite consultar el contenido de un archivo.
- **Escritura (w):** permite modificar un archivo.
- **Ejecución (x):** permite ejecutar un archivo o acceder a un directorio.
- **Propietario:** usuario al que pertenece un archivo o directorio.

## Comandos estudiados

- `whoami`: muestra el nombre del usuario actual.
- `id`: muestra el identificador del usuario y sus grupos.
- `groups`: muestra los grupos a los que pertenece el usuario.
- `ls -l`: muestra los permisos, el propietario y el grupo de los archivos.
- `chmod`: permite modificar los permisos de archivos y directorios.
- `chown`: permite cambiar el propietario de un archivo o directorio.

## Ejemplos de uso

- `whoami`: consultar el usuario actual.
- `id`: consultar los identificadores y grupos.
- `ls -l`: revisar los permisos de los archivos.
- `chmod 644 archivo.txt`: asignar lectura y escritura al propietario y solo lectura al grupo y a otros usuarios.
- `chmod 755 script.sh`: asignar permisos completos al propietario y lectura y ejecución al grupo y a otros usuarios.

Los comandos que modifican permisos o propietarios deben probarse únicamente sobre archivos de práctica y con la autorización necesaria.

## Resultados

Se documentarán los comandos ejecutados, los permisos observados y los resultados obtenidos durante los ejercicios.

## Conclusión

Esta práctica permite comprender la importancia de los usuarios, los grupos y los permisos para controlar el acceso a los recursos de un sistema Linux.
