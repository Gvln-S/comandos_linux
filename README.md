# Guía de Comandos de Linux del Equipo 🐧

Este documento es una guía de referencia rápida para los comandos de Linux que utilizamos. Cada sección está a cargo de diferentes miembros del equipo.

---

## Brayan Presiga y Daniel Sánchez

### `cd`
* **Para qué sirve:** blablabla.
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `echo`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `pwd`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `ls`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `touch`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `cp`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `mv`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `rm`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `mkdir`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `file`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `cat`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `tail`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `head`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

---

## Darek, Amigo de Nicolas y Valentina

### `printenv`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### Gestión de Usuarios (`/etc/passwd`, `/etc/shadow`)
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `useradd`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `userdel`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `passwd`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `usermod`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### Gestión de Grupos (`/etc/group`, `groupadd`, `groupdel`)
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `chmod` (y `permisos`)
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

---

## Lu, Nicolas y Santiago

### `ps`
* **Para qué sirve:** lista procesos del sistema
* **Opciones:**
    * `-l`: ver más información de los procesos 
    * `-A`: ver todos los procesos que esta corriendo el sistema y no solo los del ususario
* **Ejemplos:**
    ```bash
    # Ejemplo 
    user@:~$ ps
    PID TTY          TIME CMD
    1 ?        00:00:00 bash
    4 ?        00:00:00 ps
    ```

### `kill`
* **Para qué sirve:** termina con un proceso que se este ejecutando, necesita como parametro el PID del proceso
* **Ejemplos:**
    ```bash
    # Ejemplo
    user@:~$ ps -l
    F S   UID   PID  PPID  C PRI  NI ADDR SZ WCHAN  TTY          TIME CMD
    0 R  1000     1     0  0  60   0 -     0 -      ?        00:00:00 bash
    0 R  1000    15     0  0  60   0 -     0 -      ?        00:00:00 bash
    0 R  1000    17     0  0  60   0 -     0 -      ?        00:00:00 ps
    user@:~$ kill 15
    user@:~$ ps -l
    F S   UID   PID  PPID  C PRI  NI ADDR SZ WCHAN  TTY          TIME CMD
    0 R  1000     1     0  0  60   0 -     0 -      ?        00:00:00 bash
    0 R  1000    18     0  0  60   0 -     0 -      ?        00:00:00 ps
    ```

### `fdisk -l`
* **Para qué sirve:** lista los discos virtual del sistema
* **Ejemplos:**
    ```bash
    # Ejemplo
    user@:~$ fdisk -l
    Device     Boot    Start      End  Sectors  Size Id Type
    /dev/sda1  *        2048 39942143 39940096   19G 83 Linux
    /dev/sda2       39944190 41940991  1996802  975M  5 Extended
    /dev/sda5       39944192 41940991  1996800  975M 82 Linux swap / Solaris   
    ```

### `mount` y `umount`
* **Para qué sirve:** (por si solo) lista dispositivos de almacenamiento actualmente montados en el sistema. Tiene que trabajar con un "device" de
tipo "Linux"
* **Opciones:**
    * `-t (sistema_de_archivos)`: lista unicamente los dispositivos de almacenamiento que usan el sistema de archivos que enviaste como parametro
    * `-t (sistema_de_archivos) (dispositivo) (directorio)`: monta una partición en un dispositivo del sistema y lo guarda en el directorio
    que enviaste como parametro
* **Ejemplos:**
    ```bash
    # Ejemplo
    user@:~$ sudo mount -t ext4 /dev/sda1 /ejemplo/particion/
    user@:~$ mount -t ext4
    /dev/sda1 on /ejemplo/particion type ext4 (rw,relatime,errors=remount-ro)
    ```
* **Para qué sirve:** desmonta una partición 
* **Opciones:**
    * `(dispositivo) | (directorio)`: desmonta una partición de un dispositivo del sistema, usando el nombre del dispositivo o el directorio de creación
    de la montura
    
* **Ejemplos:**
    ```bash
    # Ejemplo
    user@:~$ sudo umount /ejemplo/particion
    user@:~$ mount -t ext4
    /dev/sda1 on / type ext4 (rw,relatime,errors=remount-ro)
    ```


### `df`
* **Para qué sirve:** muestra cada sistema de archivo montado que contega datos
* **Opciones:**
    * `-h`: permite leer la información de salida más fácil
* **Ejemplos:**
    ```bash
    # Ejemplo
    user@:~$ df -h
    Filesystem      Size  Used Avail Use% Mounted on
    udev            938M     0  938M   0% /dev
    tmpfs           192M  564K  192M   1% /run
    /dev/sda1        19G  4.4G   14G  25% /
    tmpfs           960M     0  960M   0% /dev/shm
    tmpfs           5.0M     0  5.0M   0% /run/lock
    tmpfs           192M     0  192M   0% /run/user/1000
    ```

### `du`
* **Para qué sirve:** lista el uso del disco en un directorio específico
* **Opciones:**
    * `-h`: permite leer la información de salida más fácil
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `sort`
* **Para qué sirve:** organiza los elementos de un archivo
* **Opciones:**
    * `-M`: organiza los meses en orden
    * `-n`: organiza numeros de menor a mayor
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `grep`
* **Para qué sirve:** buscar coincidencias de caracteres en un archivo
* **Opciones:**
    * `-t`: busqueda al reves, te devuelve las lineas que no son coincidencias en un archivo
    * `-n`: devuelve las lineas en las que se encuentran las coincidencias 
    * `-c`: cuenta el numero de coincidencias encontradas  
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `zip` y `gzip`
* **Para qué sirve:** comprime y descomprime archivos
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `which`
* **Para qué sirve:** busca el directorio de instalación de una utilidad
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `shells`, `subshells`, `parent shells` y `process lists`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `jobs` y `coproc`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```
### `sleep`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `type`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `history`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `alias`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```
