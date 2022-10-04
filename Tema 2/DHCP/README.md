# DHCP #
## Christian José Moreno Expósito ##

### Instalación del servivio DHCP en Windows 2016 server ###

·  Vamos al apartado de Agregar un Rol o característica.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.1.png)

·  Seleccionamos la carácterística DHCP.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.2.png)

·  Terminamos con la instalación del DHCP.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.3.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.4.png)

### Configuración del servicio DHCP ###

·  Desde la herramienta del DHCP creamos un nuevo ambito.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.5.png)

·  Seleccionamos el rango de IP que dará el servicio DHCP.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.6.png)

·  Seleccionamos un rango de IPs para excluirlas.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.7.png)

·  Configuramos una puerta de enlace a suministrar a los clientes.
 
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.8.png)

·  Configuramos un nombre de dominio.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/1.9.png)

·  Ahora reservamos una  dirección asociandola a un equipo específico (MAC)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.0.png)

  (Observamos la dirección física que tiene la máquina a la que le queremos poner la dirección fija.)
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.1.png)

  (Rellenamos con la dirección que le queremos reservar y la dirección fisica.)
 
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.2.png)

  (Comprobamos que le reserva la IP que le asignamos)
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.3.png)

·  Configuramos alguna opción para el ambito.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.4.png)

  (Decidí poner el de zona horaria).
 
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.5.png)

·  Configuramos alguna opción para el servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.6.png)

  (Decidí poner el de zona horaria).
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.7.png)

## Segunda parte ##

·  Instalamos una segunda tarjeta de red en el servidor

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.8.png)

·  Configurar la nueva interfaz de red estáticamente, en una red diferente a la inicial.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/2.9.png)

·  Crear un nuevo ámbito asociado a esta segunda red a la que presta servicio.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.0.png)

  (Direcciones Excluidas.)
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.1.png)

  (Configuramos la puerta de enlace para los equipos)
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.2.png)

  (Configuramos un dominio)
 
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.3.png)

·  Cambiamos la red a la que se conectará el cliente

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.4.png)

·  Comprobamos que recibe el cliente una dirección ip.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.5.png)

·  Creamos un nuevo SUPERAMBITO.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.6.png)

   (Seleccionamos un nombre para el superambito.)
   
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.7.png)

   (Seleccionamos los ambitos que queremos juntar en el superambito)
   
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.8.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/3.9.png)

·  Desactivamos el superambito para comprobar si deja defuncionar el DHCP.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/4.0.png)

   (Comprobamos que el cliente no recibe ninguna dirección IP)
   
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/4.1.png)

·  Activamos el superambito para comprobar si el DHCP vuelve a funcionar.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/4.2.png)

   (Comprobamos que el cliente recibe una dirección IP)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP/IMG/4.3.png)
  





















