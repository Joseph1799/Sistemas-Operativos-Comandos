# Recopilación de comandos utilizados en el curso de Sistemas Operativos.

## Comandos Ubuntu

| Comandos                   | Descripción                                              | Ejemplo de uso                                                                                   |
|---------------------------|----------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| clear                     | Limpia la pantalla de la sesión de consola actual.       | `clear`                                                                                           |
| cd \<ruta de directorio>   | Cambia el directorio actual.                            | `cd ~/Documentos` para ir al directorio "Documentos" en el directorio home del usuario actual. |
| ls \<directorio>           | Lista archivos y directorios en un directorio.          | `ls ~/Documentos` para listar el contenido del directorio "Documentos".                        |
| cp \<origen> \<destino>     | Copia un archivo o directorio.                          | `cp archivo.txt /ruta/destino` para copiar "archivo.txt" al destino especificado.              |
| mv \<origen> \<destino>     | Mueve un archivo o directorio.                          | `mv archivo.txt /ruta/destino` para mover "archivo.txt" al destino especificado.               |
| rm \<archivo>              | Elimina un archivo.                                     | `rm archivo.txt` para eliminar el archivo "archivo.txt".                                        |
| mkdir \<nombre>            | Crea un nuevo directorio.                               | `mkdir nuevo_directorio` para crear un directorio llamado "nuevo_directorio".                   |
| rmdir \<directorio>        | Elimina un directorio vacío.                            | `rmdir directorio_vacio` para eliminar un directorio vacío llamado "directorio_vacio".          |
| echo \<texto>              | Imprime en pantalla un texto.                          | `echo "Hola, mundo!"` imprimiría "Hola, mundo!" en la salida de la terminal.                    |
| cat \<archivo>             | Muestra el contenido de un archivo.                    | `cat archivo.txt` para mostrar el contenido del archivo "archivo.txt".                           |
| grep \<patrón> \<archivo>   | Busca patrones en un archivo.                          | `grep "palabra" archivo.txt` para buscar la palabra "palabra" en el archivo "archivo.txt".      |
| ps                        | Muestra los procesos en ejecución.                     | `ps aux` para listar todos los procesos en ejecución.                                           |
| top                       | Muestra información en tiempo real sobre el sistema.   | `top` para ver una lista en tiempo real de los procesos y su uso de recursos.                    |
| chmod \<permisos> \<archivo>| Cambia los permisos de un archivo.                     | `chmod 755 archivo.sh` para dar permisos de lectura, escritura y ejecución al propietario y de lectura y ejecución a otros en "archivo.sh". |
| df -h                     | Muestra el espacio libre y usado en los sistemas de archivos montados. | `df -h` para mostrar el espacio en disco en un formato legible por humanos.                      |
| du -h \<directorio>       | Muestra el espacio usado por un directorio y sus subdirectorios. | `du -h /ruta/directorio` para mostrar el uso de espacio en el directorio especificado.           |
| uname -a                  | Muestra información sobre el sistema.                  | `uname -a` para mostrar información sobre el kernel y el sistema operativo.                       |
| ifconfig                  | Muestra la configuración de las interfaces de red.     | `ifconfig` para mostrar información sobre las interfaces de red.                                  |
| ping \<host>               | Envía paquetes ICMP a un host para comprobar la conectividad. | `ping www.ejemplo.com` para comprobar la conectividad con el host "www.ejemplo.com".             |
| ssh \<usuario>@\<host>     | Inicia una sesión SSH en un host remoto.                | `ssh usuario@ejemplo.com` para iniciar una sesión SSH en el host "ejemplo.com".                  |
| wget \<URL>               | Descarga archivos desde Internet.                      | `wget https://www.ejemplo.com/archivo.zip` para descargar un archivo desde la URL especificada. |
| systemctl start/stop/restart \<servicio> | Inicia, detiene o reinicia un servicio. | `systemctl start apache2` para iniciar el servicio Apache.                                       |
| mount \<dispositivo> \<punto de montaje> | Monta un sistema de archivos.   | `mount /dev/sda1 /mnt` para montar la partición /dev/sda1 en el punto de montaje /mnt.      |
| umount \<punto de montaje> | Desmonta un sistema de archivos.                      | `umount /mnt` para desmontar la partición montada en el punto de montaje /mnt.                |
| du -h \<directorio>        | Muestra el espacio usado por un directorio y sus subdirectorios. | `du -h /ruta/directorio` para mostrar el uso de espacio en el directorio especificado.   |
| uname -a                  | Muestra información sobre el sistema.                  | `uname -a` para mostrar información sobre el kernel y el sistema operativo.               |
| ifconfig                  | Muestra la configuración de las interfaces de red.     | `ifconfig` para mostrar información sobre las interfaces de red.                          |
| ping \<host>               | Envía paquetes ICMP a un host para comprobar la conectividad. | `ping www.ejemplo.com` para comprobar la conectividad con el host "www.ejemplo.com".    |
| ssh \<usuario>@\<host>     | Inicia una sesión SSH en un host remoto.                | `ssh usuario@ejemplo.com` para iniciar una sesión SSH en el host "ejemplo.com".          |
| wget \<URL>               | Descarga archivos desde Internet.                      | `wget https://www.ejemplo.com/archivo.zip` para descargar un archivo desde la URL.      |
| systemctl start/stop/restart \<servicio> | Inicia, detiene o reinicia un servicio. | `systemctl start apache2` para iniciar el servicio Apache.                                |
| ps aux                    | Muestra todos los procesos en ejecución de todos los usuarios. | `ps aux` para listar procesos con detalles.                                       |
| top                       | Muestra información en tiempo real sobre el sistema.   | `top` para ver una lista en tiempo real de procesos y su uso de recursos.            |
| history                   | Muestra el historial de comandos ejecutados.           | `history` para ver una lista de comandos ejecutados anteriormente.                   |
| whoami                    | Muestra el nombre de usuario actual.                  | `whoami` para mostrar el nombre del usuario actual.                                  |
| uname -r                  | Muestra la versión del kernel.                        | `uname -r` para mostrar la versión del kernel.                                        |
| chmod +x \<archivo>        | Da permisos de ejecución a un archivo.                | `chmod +x script.sh` para permitir la ejecución del script "script.sh".               |
| chown \<usuario>:\<grupo> \<archivo> | Cambia el propietario y grupo de un archivo. | `chown usuario:grupo archivo.txt` para cambiar el propietario y grupo de "archivo.txt". |
| lsblk                     | Lista información de los dispositivos de bloque.     | `lsblk` para mostrar información de dispositivos de bloque como discos y particiones.  |
| fdisk -l                  | Muestra la tabla de particiones de los discos.       | `fdisk -l` para mostrar la información de particiones de discos.                      |
| date                      | Muestra la fecha y hora actual.                      | `date` para mostrar la fecha y hora actuales.                                          |

## Comandos Manjaro

| Comando                                                   | Descripción                                               | Ejemplo de uso                                                                      |
|-----------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------------------------------------|
| sudo pacman -S yay                                       | Instala el paquete "yay" utilizando el gestor de paquetes "pacman". | `sudo pacman -S yay`                                                               |
| sudo yay -S --needed base-devel                         | Instala las herramientas de desarrollo base con "yay". | `sudo yay -S --needed base-devel`                                                |
| yay -Syu                                                 | Actualiza los paquetes del sistema utilizando "yay".   | `yay -Syu`                                                                         |
| yay -S google-chrome                                    | Instala Google Chrome con "yay".                     | `yay -S google-chrome`                                                            |
| sudo pacman -S apache                                   | Instala el servidor web Apache con "pacman".          | `sudo pacman -S apache`                                                           |
| sudo nano /srv/http/index.html                          | Abre el archivo "index.html" en el directorio del servidor Apache para editar. | `sudo nano /srv/http/index.html`                                                 |
| sudo systemctl start apache                             | Inicia el servicio Apache.                           | `sudo systemctl start apache`                                                    |
| sudo systemctl start httpd.service                      | Inicia el servicio HTTPD.                           | `sudo systemctl start httpd.service`                                             |
| sudo systemctl status httpd.service                     | Muestra el estado del servicio HTTPD.               | `sudo systemctl status httpd.service`                                            |
| nano /srv/http/index.html                               | Abre el archivo "index.html" para editar.           | `nano /srv/http/index.html`                                                      |
| ip a                                                     | Muestra las direcciones IP y configuración de red. | `ip a`                                                                             |
| git clone https://github.com/mortasoft/linux-scripts     | Clona el repositorio "linux-scripts" desde GitHub.  | `git clone https://github.com/mortasoft/linux-scripts`                           |
| sudo pacman -S tree                                     | Instala el programa "tree" con "pacman".            | `sudo pacman -S tree`                                                             |
| sudo useradd -m Mortasoft -G wheel -p 123               | Crea un usuario "Mortasoft" en el grupo "wheel".    | `sudo useradd -m Mortasoft -G wheel -p 123`                                       |
| chmod -R u+rwx /home/jvargasc852                        | Cambia los permisos de un directorio de forma recursiva. | `chmod -R u+rwx /home/jvargasc852`                                               |
| chmod -R g+rX,o-rwx /home/jvargasc852                   | Cambia los permisos de un directorio de forma recursiva. | `chmod -R g+rX,o-rwx /home/jvargasc852`                                          |
| mkdir diruno                                            | Crea un directorio llamado "diruno".                | `mkdir diruno`                                                                     |
| mkdir dirdos                                            | Crea un directorio llamado "dirdos".                | `mkdir dirdos`                                                                     |
| mkdir 003                                               | Crea un directorio llamado "003".                   | `mkdir 003`                                                                        |
| mkdir 004                                               | Crea un directorio llamado "004".                   | `mkdir 004`                                                                        |
| cd diruno/                                              | Cambia al directorio "diruno".                      | `cd diruno/`                                                                       |
| mv 003 dir003                                           | Cambia el nombre del directorio "003" a "dir003".   | `mv 003 dir003`                                                                    |
| mv 004 dir004                                           | Cambia el nombre del directorio "004" a "dir004".   | `mv 004 dir004`                                                                    |
| touch archivo0                                          | Crea un archivo llamado "archivo0".                 | `touch archivo0`                                                                   |
| ls /bin > archivo1                                      | Lista los archivos en el directorio /bin y los guarda en "archivo1". | `ls /bin > archivo1`                                                            |
| cat archivo1                                            | Muestra el contenido del archivo "archivo1".        | `cat archivo1`                                                                     |
| mkdir dirtres                                           | Crea un directorio llamado "dirtres".               | `mkdir dirtres`                                                                    |
| mkdir dircuatro                                        | Crea un directorio llamado "dircuatro".            | `mkdir dircuatro`                                                                 |
| ls -la /etc/a* > $HOME/dir003/dircuatro/archivo2         | Lista los archivos en /etc que comienzan con "a" y los guarda en "archivo2". | `ls -la /etc/a* > $HOME/dir003
| ls -l $HOME 1> $HOME/dir003/dircuatro/archivo3          | Lista los archivos en el directorio home y los guarda en "archivo3". | `ls -l $HOME 1> $HOME/dir003/dircuatro/archivo3`                                 |
| cp /etc/profile $HOME/dir003/dircuatro/                 | Copia el archivo /etc/profile a "archivo4".         | `cp /etc/profile $HOME/dir003/dircuatro/`                                         |
| su Pacman22                                            | Cambia al usuario "Pacman22".                       | `su Pacman22`                                                                      |
| grep Pacman22 /etc/passwd                              | Busca información del usuario "Pacman22" en /etc/passwd. | `grep Pacman22 /etc/passwd`                                                     |
| nano archivo2                                           | Abre el archivo "archivo2" en el directorio actual para editar. | `nano archivo2`                                                                   |
| sudo cp /etc/a* ~/dirdos/                               | Copia los archivos en /etc que comienzan con "a" a "dirdos". | `sudo cp /etc/a* ~/dirdos/`                                                       |
| mv ~/diruno/archivo0 ~/dir004/                         | Mueve el archivo "archivo0" de "diruno" a "dir004". | `mv ~/diruno/archivo0 ~/dir004/`                                                 |
| sudo setfacl -m u:jvargasc852:rwX -m o::--- dirdos      | Cambia los permisos con ACL en "dirdos".            | `sudo setfacl -m u:jvargasc852:rwX -m o::--- dirdos`                              |
| sudo setfacl -m u:Centauri17:rwX -m o::--- dir003       | Cambia los permisos con ACL en "dir003".            | `sudo setfacl -m u:Centauri17:rwX -m o::--- dir003`                               |
| sudo setfacl -m u:Mortasoft:rwx -m o::rwX dir004        | Cambia los permisos con ACL en "dir004".            | `sudo setfacl -m u:Mortasoft:rwx -m o::rwX dir004`                                |
| history > historial.txt                                | Guarda el historial de comandos en "historial.txt". | `history > historial.txt`                                                         |
| pamac search \<paquete>                           | Busca un paquete en los repositorios con Pamac.              | `pamac search firefox`                                                        |
| pamac install \<paquete>                          | Instala un paquete utilizando Pamac.                        | `pamac install vlc`                                                            |
| pamac update                                      | Actualiza el sistema con Pamac.                             | `pamac update`                                                                 |
| pamac upgrade -a                                 | Realiza una actualización completa con Pamac.              | `pamac upgrade -a`                                                             |
| pamac build \<archivo.tar.gz>                     | Compila e instala un paquete local con Pamac.               | `pamac build paquete.tar.gz`                                                  |
| manjaro-settings-manager                         | Abre el Gestor de Configuración de Manjaro.                 | `manjaro-settings-manager`                                                    |
| mhwd -l                                           | Lista los controladores de hardware disponibles.           | `mhwd -l`                                                                       |
| mhwd -i \<controlador>                            | Instala un controlador de hardware.                        | `mhwd -i video-nvidia`                                                         |
| inxi -F                                           | Muestra información detallada del sistema.                 | `inxi -F`                                                                       |
| systemctl enable \<servicio>                     | Habilita un servicio para que se inicie en el arranque.   | `systemctl enable sshd`                                                        |
| systemctl disable \<servicio>                    | Deshabilita un servicio para que no se inicie en el arranque. | `systemctl disable bluetooth`                                                |
| timeshift -l                                     | Lista las instantáneas creadas con Timeshift.               | `timeshift -l`                                                                  |
| timeshift --create                                | Crea una instantánea del sistema con Timeshift.            | `timeshift --create`                                                           |
| octopi                                           | Abre el centro de software Octopi.                         | `octopi`                                                                        |
| yay -R \<paquete>                                 | Desinstala un paquete utilizando yay.                      | `yay -R firefox`                                                                |
| yay -Scc                                         | Limpia la caché de paquetes descargados con yay.           | `yay -Scc`                                                                      |
| downgrade                                        | Permite retroceder a una versión anterior de un paquete.   | `downgrade paquete`                                                            |
| systemctl mask \<servicio>                       | Bloquea un servicio para que no se pueda iniciar.          | `systemctl mask cups`                                                          |
| mhwd -l -d --pci                                 | Lista los controladores disponibles para hardware PCI.     | `mhwd -l -d --pci`                                                              |
| pamac build \<URL>                               | Compila e instala un paquete desde una URL con Pamac.      | `pamac build https://URL/paquete.tar.gz`                                       |
| sudo pacman-mirrors -g                           | Genera el archivo de configuración de los espejos.         | `sudo pacman-mirrors -g`                                                       |
| pamac list -i                                    | Lista los paquetes instalados con Pamac.                  | `pamac list -i`                                                                 |
| pamac history                                    | Muestra el historial de operaciones con Pamac.             | `pamac history`                                                                 |
| pamac clean -p                                   | Limpia la caché de paquetes descargados con Pamac.         | `pamac clean -p`                                                                |
| mhwd-kernel -li                                  | Muestra la lista de núcleos de Linux instalados.          | `mhwd-kernel -li`                                                               |
| timeshift --delete                                | Elimina una instantánea creada con Timeshift.              | `timeshift --delete`                                                           |
| pamac info \<paquete>                            | Muestra información detallada sobre un paquete con Pamac. | `pamac info gnome-shell`                                                       |
| systemd-analyze blame                            | Muestra el tiempo que tardan los servicios en arrancar.   | `systemd-analyze blame`                                                        |

## Comandos Docker 

| Comando                                                   | Descripción                                             | Ejemplo de uso                                      |
|-----------------------------------------------------------|---------------------------------------------------------|-----------------------------------------------------|
| docker --version                                         | Muestra la versión de Docker instalada.               | `docker --version`                                     |
| docker info                                              | Muestra información detallada del sistema Docker.      | `docker info`                                         |
| docker run \<imagen>                                     | Ejecuta un contenedor basado en la imagen especificada. | `docker run ubuntu:latest`                           |
| docker ps                                                | Lista los contenedores en ejecución.                  | `docker ps`                                            |
| docker ps -a                                             | Lista todos los contenedores, incluidos los detenidos. | `docker ps -a`                                        |
| docker images                                            | Lista las imágenes descargadas.                       | `docker images`                                        |
| docker pull \<imagen>                                    | Descarga una imagen de Docker desde Docker Hub.        | `docker pull nginx`                                   |
| docker build -t \<nombre>:\<etiqueta> \<directorio>        | Crea una nueva imagen a partir de un Dockerfile.      | `docker build -t myapp:latest .`                     |
| docker stop \<contenedor>                                | Detiene un contenedor en ejecución.                  | `docker stop mycontainer`                               |
| docker start \<contenedor>                               | Inicia un contenedor detenido.                        | `docker start mycontainer`                             |
| docker restart \<contenedor>                             | Reinicia un contenedor.                              | `docker restart mycontainer`                            |
| docker exec -it \<contenedor> \<comando>                  | Ejecuta un comando dentro de un contenedor en ejecución. | `docker exec -it mycontainer bash`                 |
| docker logs \<contenedor>                                | Muestra los registros de un contenedor.               | `docker logs mycontainer`                              |
| docker rm \<contenedor>                                  | Elimina un contenedor detenido.                      | `docker rm mycontainer`                                 |
| docker rmi \<imagen>                                     | Elimina una imagen.                                  | `docker rmi myapp:latest`                               |
| docker network ls                                        | Lista las redes de Docker.                           | `docker network ls`                                     |
| docker network create \<nombre>                          | Crea una nueva red de Docker.                        | `docker network create mynetwork`                       |
| docker network connect \<red> \<contenedor>               | Conecta un contenedor a una red existente.            | `docker network connect mynetwork mycontainer`        |
| docker network disconnect \<red> \<contenedor>            | Desconecta un contenedor de una red.                 | `docker network disconnect mynetwork mycontainer`      |
| docker volume ls                                         | Lista los volúmenes de Docker.                       | `docker volume ls`                                      |
| docker volume create \<nombre>                           | Crea un nuevo volumen de Docker.                    | `docker volume create myvolume`                          |
| docker volume inspect \<volumen>                         | Muestra información detallada sobre un volumen.      | `docker volume inspect myvolume`                |
| docker volume rm \<volumen>                              | Elimina un volumen de Docker.                       | `docker volume rm myvolume`                      |
| docker-compose --version                                 | Muestra la versión de Docker Compose.                | `docker-compose --version`                       |
| docker-compose up                                        | Inicia contenedores según lo especificado en el archivo `docker-compose.yml`. | `docker-compose up -d`                        |
| docker-compose down                                      | Detiene y elimina los contenedores definidos en `docker-compose.yml`. | `docker-compose down`                          |
| docker-compose logs                                      | Muestra los registros de los contenedores en un servicio de Docker Compose. | `docker-compose logs -f`                        |
| docker-compose ps                                        | Lista los servicios en ejecución de Docker Compose.   | `docker-compose ps`                             |
| docker-compose build                                     | Construye imágenes definidas en `docker-compose.yml`. | `docker-compose build`                          |
| docker-compose exec \<servicio> \<comando>                | Ejecuta un comando en un servicio de Docker Compose. | `docker-compose exec app python manage.py migrate` |
| docker-compose stop                                      | Detiene los servicios definidos en `docker-compose.yml`. | `docker-compose stop`                           |
| docker-compose start                                     | Inicia los servicios definidos en `docker-compose.yml`. | `docker-compose start`                          |
| docker-compose restart                                   | Reinicia los servicios definidos en `docker-compose.yml`. | `docker-compose restart`                        |
| docker-compose down -v                                   | Detiene y elimina los contenedores y volúmenes definidos en `docker-compose.yml`. | `docker-compose down -v`                       |

## Comandos Para Crear/Gestionar Scripts (Ubuntu) 

| Comando                                    | Descripción                                          | Ejemplo de uso                                                                                    |
|--------------------------------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| nano \<nombre de script>                    | Abre el editor de texto "nano" para crear/editar un script.  | `nano script.sh`                                                                         |
| chmod +x \<script>                          | Concede permisos de ejecución a un script.        | `chmod +x script.sh`                                                                                |
| cat \<script>                               | Muestra el contenido de un script en la salida estándar. | `cat script.sh`                                                                              |
| echo \<comandos> > \<script>                 | Escribe comandos en un script (sobrescribiendo el contenido). | `echo "echo 'Hola, mundo!'" > mi_script.sh`                                            |
| cp \<script> \<directorio>                  | Copia un script a un directorio.                 | `cp script.sh ~/Documentos/`                                                                         |
| mv \<script> \<nuevo_nombre>                | Cambia el nombre de un script.                  | `mv script.sh nuevo_script.sh`                                                                        |
| rm \<script>                                | Elimina un script.                               | `rm script.sh`                                                                                       |
| bash \<script>                              | Ejecuta un script Bash.                         | `bash mi_script.sh`                                                                                   |
| sh \<script>                                | Ejecuta un script utilizando el shell sh.       | `sh script.sh`                                                                                        |
| ./\<script>                                | Ejecuta un script desde el directorio actual.    | `./script.sh`                                                                                         |

