# Curso de Comandos Básicos para Linux

## Tabla de Contenidos
1. [Introducción a Linux](#Introducción)
2. [Estructura de Directorios](#Estructura)
3. [Comandos Básicos](#Comandos)
4. [Gestión de Archivos y Directorios](#Gestión)
5. [Permisos de Archivos](#Permisos)
6. [Redirecciones y tuberías](#Redirecciones)
7. [Comandos de Red](#Red)
8. [Comandos de uso general](#General)
9. [Final](#Final)

## 1. Introducción a Linux <a name="Introducción"></a>
Linux es un sistema operativo de código abierto modelado en el sistema operativo Unix.

## 2. Estructura de Directorios <a name="Estructura"></a>
En Linux, todo es un archivo. Incluso los directorios son archivos.

- `/`: El directorio raíz donde comienza el sistema de archivos.
- `/bin`: Binarios de usuario
- `/etc`: Archivos de configuración del sistema
- `/home`: Directorios de inicio de los usuarios
- `/opt`: Software y add-on packages
- `/tmp`: Archivos temporales
- `/var`: Archivos variables como logs y bases de datos

## 3. Comandos Básicos <a name="Comandos"></a>
- `ls`: Lista todos los archivos y directorios en el directorio actual.
- `pwd`: Muestra el directorio actual.
- `cd`: Cambia el directorio.
- `man`: Muestra la guía del usuario para cualquier comando.

## 4. Gestión de Archivos y Directorios <a name="Gestión"></a>
- `cp`: Copia archivos y directorios.
- `mv`: Mueve o renombra archivos y directorios.
- `rm`: Elimina archivos y directorios.
- `touch`: Crea un archivo vacío.
- `find`: Busca archivos y directorios.

## 5. Permisos de Archivos <a name="Permisos"></a>
- `chmod`: Cambia los permisos de un archivo.
- `chown`: Cambia el propietario de un archivo.
- `chgrp`: Cambia el grupo de un archivo.

## 6. Redirecciones y tuberías <a name="Redirecciones"></a>
- `>`: Redirige la salida a un archivo, sobrescribiendo el contenido existente.
- `>>`: Redirige la salida a un archivo, agregando al contenido existente.
- `<`: Toma la entrada de un archivo.
- `|`: Conecta la salida de un comando a la entrada de otro.

## 7. Comandos de Red <a name="Red"></a>
- `ping`: Comprueba la conectividad de red a otro host.
- `ssh`: Conecta a un host remoto.
- `netstat`: Muestra las conexiones de red.

## 8. Comandos de uso general <a name="General"></a>

- `cat`: Muestra el contenido de un archivo.
- `echo`: Muestra un mensaje en la pantalla.
- `touch archivo.txt`: Crea un archivo con entensión .txt.
- `cp archivo1 archivo2`: Copia el archivo1 y lo nombra como archivo2.
- `cp -r directorio1/ directorio2`: Copia el directorio1 y lo nombra como directorio2.
- `ls directorio`: Muestra el contenido del directorio.
- `mv archivo1 archivo2`: Mueve el archivo1 y lo nombra como archivo2.
- `mv directorio1/ ruta/directorio2`: Mueve el directorio1 y lo nombra como directorio2.
- `mv -v directorio1/ ruta/directorio2`: Muestra el proceso de mover(renombrar) el directorio1 a directorio2.
- `rm -r directorio`: Elimina el directorio con todo su contenido.

## 9. Final <a name="Final"></a>
Este es solo el comienzo de lo que se puede hacer con Linux. Hay muchos más comandos y características por descubrir.
