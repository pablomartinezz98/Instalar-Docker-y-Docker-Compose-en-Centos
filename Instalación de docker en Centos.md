# Instalación de docker en Centos

La instalación de docker en Centos es sencilla.

Primero debemos añadir un repositorio:
dnf config-manager --add-repo=https://download.docker.com/linux/centos/docker-ce.repo

Una vez añadido el repositorio ejecutamos el comando dnf install docker-ce --nobest -y

Iniciamos el servicio: systemctl start docker

Miramos el servicio 
![Instalación](/Fotos/Captura.PNG)

Y vemos la version de Docker
![Instalación](/Fotos/Captura1.PNG)
