# DHCP Linux - Christian Moreno #
## Instalación del servicio DHCP en Ubuntu Linux ##

 - Instalamos en la MV servidor instalamos el servicio DHCP.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.1.png)

 - Ponemos una IP estática al servidor. (en mi caso escogí esas por que lo hice desde casa).

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.2.png)

 - Configuramos el adaptador del servidor en red interna con nombre intnet.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.3.png)

## Configuración del servicio DHCP ##

 - Entramos en el archivo de configuracióndel DHCP y configuramos los siguientes parámetros
    · El ambito con la dirección IP asociada y el rango que va ha dar.
    · La puerta de enlace y servidores DNS.
    · Y configuraciones necesarias 
    
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.4.png)

  - Entramos en el fichero de configuración de las interfaces de red del DHCP.
     · Escribimos nustra interfaz de RED.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.5.png)
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.6.png)

  - Reiniciamos el servicio DHCP y Revisamos el estado.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.7.png)

## Comprobación del funcionamiento del DHCP en el Cliente ##

 (La máquina cliente debe estar en red interna con nombe intnet)
 
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.8.png)

## Reservar una IP a un equipo específico (MAC) ##

  - Comprobamos la MAC del equipo al que le queramos reservar una IP.
  
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/1.9.png)

  - Volvemos al archivo de configuración del DHCP y lo editamos de esta manera para reservar una IP.
 
 (Los parámetros son los siguientes, debemos asignarle un nombre a la reserva, la MAC del cliente y la 
  IP que queremos reservarle).
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%202/DHCP%20Linux/IMG/2.0.png)


  






















