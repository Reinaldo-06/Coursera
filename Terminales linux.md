Aquí te dejo algunos de los comandos de terminal más populares y útiles en Linux, organizados por categorías:

### 1. **Navegación del sistema de archivos**
- `ls` – Lista los archivos y directorios en el directorio actual.
  - Ejemplo: `ls -l` (muestra detalles de archivos en formato largo).
- `cd` – Cambia el directorio actual.
  - Ejemplo: `cd /home/user` (cambia al directorio `/home/user`).
- `pwd` – Muestra el directorio actual.
- `mkdir` – Crea un nuevo directorio.
  - Ejemplo: `mkdir nuevo_directorio`.
- `rmdir` – Elimina un directorio vacío.
  - Ejemplo: `rmdir viejo_directorio`.

### 2. **Manipulación de archivos**
- `touch` – Crea un archivo vacío o actualiza la fecha de un archivo.
  - Ejemplo: `touch archivo.txt`.
- `cp` – Copia archivos o directorios.
  - Ejemplo: `cp archivo.txt /ruta/destino/`.
- `mv` – Mueve o renombra archivos o directorios.
  - Ejemplo: `mv archivo.txt nuevo_nombre.txt`.
- `rm` – Elimina archivos o directorios.
  - Ejemplo: `rm archivo.txt` (borra un archivo).
  - Ejemplo: `rm -r directorio/` (borra un directorio recursivamente).
  
### 3. **Información del sistema**
- `df` – Muestra el espacio en disco disponible.
  - Ejemplo: `df -h` (en formato legible para humanos).
- `du` – Muestra el uso de disco de un archivo o directorio.
  - Ejemplo: `du -h archivo.txt` (uso de disco del archivo).
- `top` – Muestra los procesos en tiempo real.
- `htop` – Herramienta interactiva para monitorear procesos (requiere instalación).
- `uname` – Muestra información sobre el sistema.
  - Ejemplo: `uname -a` (muestra todos los detalles del sistema).
- `free` – Muestra el uso de memoria.
  - Ejemplo: `free -h` (en formato legible para humanos).

### 4. **Administración de usuarios**
- `whoami` – Muestra el nombre del usuario actual.
- `sudo` – Ejecuta un comando como superusuario o con permisos de otro usuario.
  - Ejemplo: `sudo apt update` (ejecuta la actualización de paquetes como root).
- `adduser` – Añade un nuevo usuario.
  - Ejemplo: `sudo adduser nuevo_usuario`.
- `passwd` – Cambia la contraseña de un usuario.
  - Ejemplo: `passwd` (cambia tu propia contraseña).
  
### 5. **Gestión de procesos**
- `ps` – Muestra una lista de procesos en ejecución.
  - Ejemplo: `ps aux` (muestra todos los procesos del sistema).
- `kill` – Finaliza un proceso por su PID.
  - Ejemplo: `kill 1234` (termina el proceso con PID 1234).
- `killall` – Termina todos los procesos con un nombre específico.
  - Ejemplo: `killall firefox`.

### 6. **Permisos de archivos**
- `chmod` – Cambia los permisos de un archivo.
  - Ejemplo: `chmod 755 archivo.sh` (otorga permisos de lectura y ejecución).
- `chown` – Cambia el propietario de un archivo o directorio.
  - Ejemplo: `chown usuario:grupo archivo.txt`.

### 7. **Redes**
- `ping` – Envía paquetes ICMP a una dirección IP o dominio.
  - Ejemplo: `ping google.com`.
- `ifconfig` – Muestra la configuración de red (requiere permisos de root en algunas distribuciones).
- `curl` – Transferencia de datos desde o hacia un servidor.
  - Ejemplo: `curl http://example.com`.
- `wget` – Descarga archivos desde la web.
  - Ejemplo: `wget http://example.com/archivo.zip`.
  
### 8. **Gestión de paquetes (depende de la distribución)**
- **Debian/Ubuntu**:
  - `apt` – Herramienta para gestionar paquetes.
    - Ejemplo: `sudo apt update` (actualiza la lista de paquetes).
    - Ejemplo: `sudo apt install nombre_paquete` (instala un paquete).
- **Fedora/RHEL/CentOS**:
  - `yum` o `dnf` – Gestor de paquetes.
    - Ejemplo: `sudo dnf install nombre_paquete`.
- **Arch Linux**:
  - `pacman` – Gestor de paquetes.
    - Ejemplo: `sudo pacman -S nombre_paquete`.

### 9. **Búsqueda de archivos y texto**
- `find` – Busca archivos y directorios en el sistema.
  - Ejemplo: `find /ruta -name "archivo.txt"`.
- `grep` – Busca patrones de texto dentro de archivos.
  - Ejemplo: `grep "texto" archivo.txt`.
- `locate` – Encuentra archivos rápidamente (requiere base de datos actualizada).
  - Ejemplo: `locate archivo.txt`.

### 10. **Comandos de compresión y descompresión**
- `tar` – Archiva y descomprime archivos `.tar`.
  - Ejemplo: `tar -czvf archivo.tar.gz /ruta/directorio` (comprime).
  - Ejemplo: `tar -xzvf archivo.tar.gz` (descomprime).
- `zip`/`unzip` – Comprime y descomprime archivos en formato `.zip`.
  - Ejemplo: `zip archivo.zip archivo1 archivo2` (comprime).
  - Ejemplo: `unzip archivo.zip` (descomprime).

Estos son solo algunos de los comandos más útiles. Linux ofrece una gran cantidad de comandos para múltiples tareas, y la mayoría tiene muchas opciones que puedes explorar para optimizar su uso.
