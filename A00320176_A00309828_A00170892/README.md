# Miniproyecto Sistemas Operativos

Integrantes:
Daniel Gutierrez,
Emmanuel Bolaños,
Carlos Llano

El siguiente proyecto consiste en el despliegue de una aplicación web para obtener información del sistema operativo (Deberá emplear la aplicación desarrollada en el segundo parcial). Para este propósito se debe emplear el sistema operativo Ubuntu Server 16.04, el microframework flask y ambientes virtuales.


<ol>
<li>
URL repositorio: 
Para instalar el sistema operativo de Ubuntu Server 16.04 se debe descargar el ISO de la página: https://www.ubuntu.com/download/server. Se selección el archivo ISO en almacenamiento y se configuran las interfaces de red igual que en CENTOS. <br>
Luego se debe seleccionar las características generales como: lenguaje de la máquina, configuración de usuarios y contraseñas, partición de discos, selección de programas.
</li>
<li>
En Ubuntu se deben configurar las interfaces de la siguiente manera:<br>


Se agregan al archivo interfaces que se encuentra en la ruta /etc/network/interfaces. Aquí se puede configurar que su ip se tome via dhcp
<img src="https://github.com/dgutierrez1/so-project/blob/master/A00320176_A00309828_A00170892/1.png?raw=true" >
<br>
Se reinicia el servicio de networking con el comando service service networking restart
<img src="https://github.com/dgutierrez1/so-project/blob/master/A00320176_A00309828_A00170892/2.png">
</li>
<li>
Para abrir los puertos en Ubuntu utilizamos el comando sudo ufw allow 5000. Después de esto debemos utilizar el comando sudo ufw enable.
</li>
<li>
Para el funcionamiento del proyecto se usaron los siguientes comandos para bajar las respectivas dependencias:<br>
a. Descargar dependencias necesarias para el funcionamiento de python<br>
i. sudo apt-get install build-essential checkinstall <br>
ii. sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev<br>
b. Instalar Python en caso de que no se quiera usar la versión por defecto, que es python3<br>
i. wget https://www.python.org/ftp/python/2.7.13/Python-2.7.13.tgz<br>
ii. tar xzf Python-2.7.13.tgz<br>
iii. cd Python-2.7.13 &  sudo ./configure <br>
iiii. sudo make install<br>
<\li>
<li>
Para crear el ambiente virtual debemos instalar pip, virtualenv y Flask.<br>
a. Instalar virtualenv <br>
i. pip install virtualenv<br>
ii. cd ~/ <br>
iii. mkdir envs<br>
iiii. cd envs<br>
v. virtualenv flask_env<br>
b. Activar el ambiente<br>
i. . flask_env/bin/actívate<br>
c. Desactivar el ambiente<br>
i. deactivate<br>



<\li>
<ol>
