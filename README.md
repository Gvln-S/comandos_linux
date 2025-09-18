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

## Darek Aljuri, Mauricio Suarez y Valentina Ruiz

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

## Luisa Carpintero, Nicolas Clavijo y Santiago Gavilán

### `ps`
* **Para qué sirve:** lista procesos del sistema
* **Opciones:**
    * `-l`: ver más información de los procesos 
    * `-A`: ver todos los procesos que esta corriendo el sistema y no solo los del ususario
* **Ejemplos:**
    ```bash
    user@:~$ ps
    PID TTY          TIME CMD
    1 ?        00:00:00 bash
    4 ?        00:00:00 ps
    ```

### `kill`
* **Para qué sirve:** termina con un proceso que se este ejecutando, necesita como parametro el PID del proceso
* **Ejemplos:**
    ```bash
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
    user@:~$ du -h
    16K     ./personal/terminals/.poshthemes
    64K     ./personal/terminals/.git/hooks
    8.0K    ./personal/terminals/.git/info
    4.0K    ./personal/terminals/.git/refs/tags
    8.0K    ./personal/terminals/.git/refs/heads
    12K     ./personal/terminals/.git/refs/remotes/origin
    16K     ./personal/terminals/.git/refs/remotes
    32K     ./personal/terminals/.git/refs
    ```

### `sort`
* **Para qué sirve:** organiza los elementos de un archivo
* **Opciones:**
    * `-M`: organiza los meses en orden
    * `-n`: organiza numeros de menor a mayor
* **Ejemplos:**
    ```bash
    user@:~$ cat prueba.txt
    4
    3
    6
    78
    83
    3
    4
    user@:~$ sort prueba.txt
    3
    3
    4
    4
    6
    78
    83
    user@:~$ sort -n prueba.txt
    3
    3
    4
    4
    6
    78
    83
    ```

### `grep`
* **Para qué sirve:** buscar coincidencias de caracteres en un archivo
* **Opciones:**
    * `-t`: busqueda al reves, te devuelve las lineas que no son coincidencias en un archivo
    * `-n`: devuelve las lineas en las que se encuentran las coincidencias 
    * `-c`: cuenta el numero de coincidencias encontradas  
* **Ejemplos:**
    ```bash
    user@:~$ cat prueba_dos.txt
    esta era la historia de juan
    esta era la historia de pedro
    esta era la historia de antonio
    esta era la historia de lucrecia
    esta era la historia de carlota
    esta era la historia de sara
    user@:~$ grep -n carlota prueba_dos.txt
    5:esta era la historia de carlota
    user@:~$ grep -c carlota prueba_dos.txt
    1
    ```

### `zip` y `gzip`
* **Para qué sirve:** comprime y descomprime archivos
* **Ejemplos:**
    ```bash
    # Ejemplo
    user@:~$ cat prueba_tres.txt
    hola, me van a comprimir
    user@:~$ zip prueba_comprimida.zip prueba_tres.txt
    adding: prueba_tres.txt (stored 0%)
    user@:~$ ls
    prueba_comprimida.zip  prueba_tres.txt
    ```

### `which`
* **Para qué sirve:** busca el directorio de instalación de una utilidad
* **Ejemplos:**
    ```bash
    # Ejemplo
    user@:~$ which bash
    /usr/bin/bash
    user@:~$ which nano
    /usr/bin/nano
    user@:~$ which cat
    /usr/bin/cat
    ```

### `shells`, `subshells`, `parent shells`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    user@:~$ bash
    user@:~$ bash
    user@:~$ bash
    user@:~$ bash
    user@:~$ bash
    user@:~$ cat /etc/shells
    # /etc/shells: valid login shells
    /bin/sh
    /usr/bin/sh
    /bin/bash
    /usr/bin/bash
    /bin/rbash
    /usr/bin/rbash
    /bin/dash
    /usr/bin/dash
    /usr/bin/tmux
    user@:~$ ps --forest
    PID TTY          TIME CMD
    1054 pts/1    00:00:00 bash
    1684 pts/1    00:00:00  \_ bash
    1686 pts/1    00:00:00      \_ bash
    1688 pts/1    00:00:00          \_ bash
    1690 pts/1    00:00:00              \_ bash
    1692 pts/1    00:00:00                  \_ bash
    1701 pts/1    00:00:00                      \_ ps
    # Noten que para el siguiente comando el PPID (Parent Process Id) es el PID (Process Id) de la shell padre
    user@:~$ ps -l
    F S   UID     PID    PPID  C PRI  NI ADDR SZ WCHAN  TTY          TIME CMD
    0 S  1000    1054    1053  0  80   0 -  2444 do_wai pts/1    00:00:00 bash
    0 S  1000    1684    1054  0  80   0 -  2060 do_wai pts/1    00:00:00 bash
    0 S  1000    1686    1684  0  80   0 -  2060 do_wai pts/1    00:00:00 bash
    0 S  1000    1688    1686  0  80   0 -  2060 do_wai pts/1    00:00:00 bash
    0 S  1000    1690    1688  0  80   0 -  2060 do_wai pts/1    00:00:00 bash
    0 S  1000    1692    1690  0  80   0 -  2459 do_wai pts/1    00:00:00 bash
    0 R  1000    1702    1692 99  80   0 -  2771 -      pts/1    00:00:00 ps
    ```
### `process lists`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `coproc`
* **Para qué sirve:** blablabla
* **Opciones:**
    "completen las opciones que vean necesarias"
    * `-opcion`:
* **Ejemplos:**
    ```bash
    # Ejemplo
    
    ```

### `jobs`
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
