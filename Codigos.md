# Comandos Generales Linux Sistemas Operativos


# COMANDOS BASICOS

 ***(apt install)***   >>> Este comando por medio de la digitación de mencionado comando Instala un paquete deseado en concreto*

 ***(sudo)***   >>> Este se encarga en brindar y dar permisos en concreto a lo que el usuario desea realizar*

 ***(sudo apt update)***  >>> Instala toda aquella información de paquetes ya instalados anteriormente*

 ***(sudo apt upgrade)***   >>> Actualiza y descarga toda la información de paquetes ya instalados anteriormente

 ***(man)***  >>> Este comando muestra toda la ayuda de un comando*

 ***(exit)***  >>> Al digitar, este saca al usuario del programa*

 ***(su -)***  >>> Con el comando su- logra cambiar de usuario completamente*



# COMANDOS DE ARCHIVOS
 ***(mv)***  >>> Este comando se encarga de mover distintos archivos en la terminal

 ***(rm)***  >>> Este se encarga de borrar y eliminar archivos concretos

 ***(ls)***  >>> Este comando cumple la función de Imprimir cualquier carpeta en específico

 ***(mkdir)*** >>> Con este comando se logra crear un determinado directorio

 ***(cp)***   >>> Este comando logra hacer copias de archivos concretos 

 ***(nano)***   >>> Este comando logra abrir un archivo directamente en la terminal

 ***(cat)***   >>> Este comando logra imprimir un archivo (concatena) especifico

 ***(convert -verbose -density 300 -trim -quality 100 -flatten -sharpen 0x1.0)***   >>> Este comando logra crear archivos de pdf

 ***(Pdfunite)***   >>> Este comando crea la union entre pdfs

 ***(touch)***   >>> Este comando se encarga en crear y realiza nuevos

 ***(pdfseparate)***   >>> Este comando por su parte logra hacer y separar pdfs

 ***(grep –r)***   >>> Este comando busca patrones dentro de archivos

***(find)***   >>> Este comando encuentra a distintos archivos

 ***(mv)***   >>> Este comando se encarga de mover distintos archivos en la terminal

 ***(rm)***   >>> Este se encarga de borrar y eliminar archivos concretos

 ***(head)***  >>> Este comando imprime las primeras lineas de un archivo en concreto

 ***(tail)***   >>> Este comando imprime las lineas de un archivo

 ***(more)***   >>> Se encarga de mostrar mas de un archivo por líneas

 ***(less)***  >>>  Se encarga de mostrar uno o menos de un archivo por linea

 ***(scp)***  >>>  Este comando puede transferir archivos via ssh 


# Directorios

 ***(rm –Rf)***  >>> Este comando remueve por completo y de manera forzada el directorio

 ***(rm –R)***  >>> Este comando remueve por completo un directorio

 ***(git clone)*** >>>  Este comando crea una copia al repositorio del GitHub

 ***(curl)***  >>> Este comando realiza interacciones con distintas paginas web

 ***(wc)***  >>> Este comando realiza un conteo de las distintas lineas

 ***(wc –m)***  >>> Realiza un conteo de todos los caracteres

 ***(wc –w)***  >>> Realiza un conteo sobre todas las palabras y la cantidad de ellas 




# SISTEMA

 ***(history) / (grep curl)*** >>> Enseña en pantallael historial de comandos específicos

 ***(history)***  >>> Enseña en pantalla el historial completo de comandos

 ***(clear)***  >>> Limpia y elimina todo lo digitado y lo encontrado en  la terminal

 ***(shutdown)*** >>> Este comando hace apagar el sistema

 ***(reboot)***  >>> Este comando hace reiniciar el sistema

 ***(ping)***  >>> Este comando trata en enviar un ping  en concreto a una dirección concreta

 ***(ip addr)***  >>> Este código muestra toda la información encontrada en la misma red

 ***(neofetch)*** >>>  Este comando “neofetch” trata en ejecutar este mismo comando

 ***(pwd)***  >>> Este comando realiza la muestra del directorio actual

 ***(cmatrix)***  >>> Este comando toma  y realiza la muestra de la matrix en terminal.

 ***(whoami)***  >>> Este comando muestra el usuario actual del dominio 


# DOCKER
 ***(docker history)*** >>>  Este comando se encarga en enseñar el historial de una imagen

 ***(docker images)***  >>> Este comando se encarga en enseñar imagenes

 ***(docker info)***  >>> Enseña informacion del sistema

 ***(docker ps)***   >>> Se encarga en mostrar todos los contenedores encointrados

 ***(docker info)***  >>> Se encarga de enseñar la informacion generaldel sistema

 ***(uname –a)*** >>>  Se encarga de imprimir toda la informacion del kernel

 ***(docker network ls)*** >>>  Este comando se encarga simplemente en imprimir

 ***(ifconfig)*** >>>  Se encarga de enseñar toda informacion de red


# *Como instalar el Docker?*

Instalacion del Docker:

 #Actualizar paquetes
sudo apt-get update

# Instalar paquetes necesarios
sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common

# Agregar la clave GPG oficial de Docker
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -

# Agregar el repositorio oficial de Docker
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"

# Actualizarlos repositorios nuevamente
sudo apt-get update

# Instalar docker
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose

# Utilizar el Docker sin sudo
sudo usermod -aG docker ${USER} su - ${USER}

# Se valida el funcionamiento
sudo docker run hello-world


#Iniciar  Daemon
sudo systemctl start docker
sudo systemctl enable docker

#Como instalar el Docker?

#Instalacion del Docker:

# Actualizar paquetes
sudo apt-get update

# Instalar paquetes necesarios
sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common

# Agregar la clave GPG oficial de Docker
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -

# Agregar el repositorio oficial de Docker
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"

# Actualizarlos repositorios nuevamente
sudo apt-get update

# Instalar docker
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose

# Utilizar el Docker sin sudo
sudo usermod -aG docker ${USER} su - ${USER}

# Se valida el funcionamiento
sudo docker run hello-world


#Iniciar  Daemon
sudo systemctl start docker
sudo systemctl enable docker


_________________________________________________________________________________________

#Comandos Linux Básicos:

pwd
cd
ls
cat
cp
mv
mkdir
rmdir
rm
touch
locate
find
grep
sudo
df
du
head
tail
diff
tar
kill
ping
wget
uname
top
echo
zip / unzip
hostname
useradd/ userdel

#  Administración de archivos y carpetas
mv
rm
rm -R: Recursive
cp
scp 

# Pagina Web
curl
git clone
wget

# Archivos
wc robots.txt
head
tail
less
more

# Busqueda
find
locate
updatedb
grep

# Networking
ping
nmap
nslookup
ip addr
netstat

# Administrar Disco Duro
df -h


history
shutdown now
reboot
tar unrar
tar -tvf myarchive.tar
dd
ffmpeg
fdupes


