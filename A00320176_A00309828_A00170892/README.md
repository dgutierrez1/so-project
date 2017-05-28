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
<ol>
