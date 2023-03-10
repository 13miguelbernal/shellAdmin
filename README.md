<h1 align="center">Taller 2</h1>

<h1 align="justify">__________________________________________________</h1>
 <h3 align="justify">Se genera una Shell en la cual se crea un menú con las opciones solicitadas en el taller que le permita al usuario escoger la acción que desea realizar en la configuración del servidor</h3>

 <h3 align="justify">1. Para la opción cambio de nombre del servidor se ejecuta el comando hostnamectl el cual muestra toda la información actual del servidor y luego se le pregunta al usuario si desea hacer el cambio del nombre del servidor.
Si el usuario digita “Y o y”, se le solicitara al usuario que escriba el nuevo nombre al servidor y este se guarda en la variable $nombre y se ejecuta el siguiente comando: sudo hostnamectl set-hostname "$nombre" 
Por ultimo se le muestra en la pantalla al usuario la información del servidor con el nuevo nombre asignado </h3>
 
 <h3 align="justify">2. Para la opción Cambiar Partición de los discos, se le presenta al usuario las particiones existentes y luego se le solicita al usuario que digite la partición que desea modificar, luego se abrirá el menú para que realice el cambio que desee </h3>
  
 <h3 align="justify">3. En esta opción el usuario tiene la opción de cambiar la dirección IP del servidor, primero se le pregunta al usuario si dese realizar la instalación del net-tools debido a que es necesario tener instalado este aplicativo para que se pueda realizar el cambio de la IP, una vez realizada la instalación se muestra en pantalla la información de las interfaces del servidor y se le solicita al usuario que ingrese el nombre de la interface que desea cambiarle la IP, la dirección nueva y la mascara que va tener. Finalmente se muestra un mensaje confirmando el cambio de la IP y la información completa del estado actualizado de las interfaces </h3>
  
 <h3 align="justify">4. En la opción modificación de cambio de host se le da acceso al usuario al archivo hosts del sistema para que pueda agregar o eliminar direcciones de hosts</h3>
 
 
 <h3 align="justify">5. En esta opción el usuario puede modificar los permisos del firewall según el menú de opciones que se le muestran en la pantalla </h3>
  
 <h3 align="justify">6. En la siguiente opción se le muestra al usuario un menú con las opciones para que pueda realizar las configuraciones de DNS con los siguientes comandos: </h3>
<h3 align="justify">1.Instalar resolvconf:		       sudo apt install resolvconf</h3>
<h3 align="justify">2.Habilitar servicio DNS:    		sudo service resolvconf start</h3>
<h3 align="justify">3.Detener servico DNS:		sudo service resolvconf stop</h3>
<h3 align="justify">4.Estado del servicio DNS:		sudo service resolvconf status</h3>
<h3 align="justify">5.Reiniciar servico DNS:		sudo service resolvconf restart</h3>
<h3 align="justify">6.Editar DNS:			sudo nano /etc/resolv.conf</h3>
 
 <h3 align="justify">7. En esta opción el usuario puede realizar la modificación del archivo donde se alojan las configuraciones del proxy, por esta razón se le presenta una plantilla de como debe digitar la informacion para que se guie y realice la configuracion de manera adecuada</h3>

<h3 align="justify">8. Se agregó esta opción para la instalación de Docker de manera automatica. </h3>
  