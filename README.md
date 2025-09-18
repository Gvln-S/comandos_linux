# Guía de Comandos de Linux del Equipo 🐧

Este documento es una guía de referencia rápida para los comandos de Linux que utilizamos. Cada sección está a cargo de diferentes miembros del equipo.

---

## 👤 Brayan y Daniel Analitica

### `cd`
* **Para qué sirve:** (Explicación breve de su función principal).
* **Opciones:**
    * `cd ..`: (Descripción de la opción).
    * `cd ~` o `cd`: (Descripción de la opción).
    * `cd -`: (Descripción de la opción).
* **Ejemplos:**
    ```bash
    # Ejemplo 1: descripción de lo que hace el comando.
    cd /var/log

    # Ejemplo 2: descripción de lo que hace el comando.
    cd ..
    ```

### `echo`
* **Para qué sirve:**
* **Opciones:**
    * `-n`:
    * `-e`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    echo "Hola Mundo"
    ```

### `pwd`
* **Para qué sirve:**
* **Opciones:**
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    pwd
    ```

### `ls`
* **Para qué sirve:**
* **Opciones:**
    * `-l`:
    * `-a`:
    * `-h`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    ls -lah
    ```


### `touch`
* **Para qué sirve:**
* **Opciones:**
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    touch mi_archivo.txt
    ```

### `cp`
* **Para qué sirve:**
* **Opciones:**
    * `-r`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    cp archivo_origen.txt /ruta/destino/
    ```

### `mv`
* **Para qué sirve:**
* **Opciones:**
    * `-i`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    mv nombre_antiguo.txt nombre_nuevo.txt
    ```

### `rm`
* **Para qué sirve:**
* **Opciones:**
    * `-r`:
    * `-f`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    rm archivo_a_borrar.txt
    ```

### `mkdir`
* **Para qué sirve:**
* **Opciones:**
    * `-p`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    mkdir -p nueva_carpeta/sub_carpeta
    ```

### `file`
* **Para qué sirve:**
* **Opciones:**
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    file mi_documento.pdf
    ```

### `cat`
* **Para qué sirve:**
* **Opciones:**
    * `-n`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    cat archivo.txt
    ```

### `tail`
* **Para qué sirve:**
* **Opciones:**
    * `-n <numero>`:
    * `-f`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    tail -f /var/log/syslog
    ```

### `head`
* **Para qué sirve:**
* **Opciones:**
    * `-n <numero>`:
* **Ejemplos:**
    ```bash
    # Ejemplo 1
    head -n 20 archivo.csv
    ```

---

## 👤 Darek, Amigo de Nicolas y Valentina

### `printenv`, `variables`, `export` y `unset`
* **Para qué sirven:**
* **Opciones:**
* **Ejemplos:**
    ```bash
    # Ver el valor de la variable PATH
    echo $PATH

    # Crear una variable y exportarla
    export MI_VARIABLE="mi valor"

    # Eliminar la variable
    unset MI_VARIABLE
    ```

### Gestión de Usuarios (`passwd`, `shadow`, `useradd`, `userdel`, `passwd`, `usermod`)
* **Para qué sirven:**
* **Opciones:**
    * `useradd -m`:
    * `userdel -r`:
* **Ejemplos:**
    ```bash
    # Crear un nuevo usuario llamado 'testuser'
    sudo useradd -m testuser

    # Asignar una contraseña a 'testuser'
    sudo passwd testuser

    # Eliminar al usuario 'testuser' y su directorio home
    sudo userdel -r testuser
    ```

### Gestión de Grupos (`group`, `groupadd`, `groupdel`)
* **Para qué sirven:**
* **Opciones:**
* **Ejemplos:**
    ```bash
    # Crear un nuevo grupo llamado 'developers'
    sudo groupadd developers

    # Eliminar el grupo 'developers'
    sudo groupdel developers
    ```

### `permisos` y `chmod`
* **Para qué sirven:**
* **Opciones/Modos:**
    * **Simbólico (u, g, o, a / +, -, = / r, w, x):**
    * **Octal (ej. 755, 644):**
* **Ejemplos:**
    ```bash
    # Hacer un script ejecutable para el propietario
    chmod u+x mi_script.sh

    # Dar permisos de lectura y escritura al grupo y solo lectura a otros
    chmod 764 mi_archivo.txt
    ```


---

## 👤 Lu, Nicolas y Santiago

### `ps` y `kill`
* **Para qué sirven:**
* **Opciones:**
    * `ps aux`:
    * `kill -9 <PID>`:
* **Ejemplos:**
    ```bash
    # Listar todos los procesos en ejecución
    ps aux

    # Encontrar el PID de un proceso (ej. firefox)
    ps aux | grep firefox

    # Terminar el proceso con PID 1234
    kill 1234
    ```

### `mount`, `df`, `umount` y `du`
* **Para qué sirven:**
* **Opciones:**
    * `df -h`:
    * `du -sh`:
* **Ejemplos:**
    ```bash
    # Ver el espacio libre en los discos
    df -h

    # Ver el tamaño de la carpeta actual
    du -sh .

    # Montar un dispositivo (ejemplo)
    sudo mount /dev/sdb1 /mnt/usb
    ```

### `sort` y `grep`
* **Para qué sirven:**
* **Opciones:**
    * `grep -i`:
    * `grep -r`:
    * `sort -n`:
* **Ejemplos:**
    ```bash
    # Buscar una palabra en un archivo
    grep "error" log.txt

    # Ordenar una lista de números
    sort -n numeros.txt
    ```

### `zip` y `gzip`
* **Para qué sirven:**
* **Opciones:**
    * `zip -r`:
* **Ejemplos:**
    ```bash
    # Comprimir un archivo
    gzip mi_archivo.log

    # Comprimir una carpeta
    zip -r mi_carpeta.zip /ruta/de/la/carpeta
    ```

### Conceptos de Shell (`shells`, `subshells`, `parent shells`, `process lists`)
* **Para qué sirven:**
* **Ejemplos:**
    ```bash
    # Ejecutar comandos en una subshell
    (pwd; ls)
    ```

### `sleep`, `jobs` y `coproc`
* **Para qué sirven:**
* **Ejemplos:**
    ```bash
    # Ejecutar un comando en segundo plano
    sleep 60 &

    # Ver los trabajos en segundo plano
    jobs
    ```

### `which`, `type`, `history` y `alias`
* **Para qué sirven:**
* **Ejemplos:**
    ```bash
    # Encontrar la ubicación de un programa
    which python

    # Ver los últimos comandos usados
    history

    # Crear un alias
    alias ll='ls -lah'
    ```
