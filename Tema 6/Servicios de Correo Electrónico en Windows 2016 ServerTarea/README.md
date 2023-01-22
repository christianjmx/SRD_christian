# Servidor de Correo SMTP - Christian José Moreno Expósito

## Instalación y configuración servicio SMTP

· Instalamos la característica servicio smtp.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/1.png)

· Ingresamos a propiedades del (ISS).

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/2.png)

· Configuramos lo siguiente:
    Establecer como IP todas las asignadas
    Limitar el número de conexiones a 50
    Habilitar el registro en formato W3C, diario y en una carpeta determinada
    
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/3.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/4.png)

    Configurar envío de mensajes dentro de nuestra red local: Aceptar la conexión al servidor y la retransmisión de mensajes a todos los equipos menos los que aparecen en la lista (incluir una IP cualquiera en la lista para impedir su acceso y retransmisión)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/5.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/6.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/7.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/8.png)

    Establecer autenticación anónima.
    
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/9.png)

    Comprobar la existencia del dominio AD predeterminado. Crea un dominio de tipo alias para disponer de cuentas en otro dominio.
    
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/10.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/11.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/12.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/13.png)

     Comprueba carpetas de correo creados en C:\Inetpub\mailroot.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/14.png)

· Creamos un nuevo registro de correo en el DNS.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/15.png)

## Desde el cliente Windows ##

· Comprobar acceso al nuevo nombre DNS creado en el servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/16.png)

· Configurar el cliente de correo Live mail agregando dos cuentas de correo cualquiera (usuarios AD -dominio- y no AD). Se deberá especificar: usuario / buzón, contraseña,  servidor SMTP.

    Descargamos pegasumail.
    
![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/17.png)

    Comenzamos la instalación de esta manera.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/18.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/19.png)

    Escribimos el nombre de un usuario que este en el AD seguido del alias.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/20.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/21.png)

    Escribimos la ip del servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/22.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/23.png)

## Comprobaciones ##

· Correo para pedro usuario del AD.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/24.png)

· Comprobamos en el servidor la carpeta mailroot.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/25.png)


· Correo a un usuario del sistema pero no del AD.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/26.png)

· Comprobamos en el servidor la carpeta mailroot.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/27.png)

· Correo a un usuario que no existe.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/28.png)

· Comprobamos en el servidor la carpeta mailroot.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/29.png)

· Correo a mi cuenta personal.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/30.png)

· Comprobación del correo en mi cuenta personal.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/31.png)

· Habilitamos el certificado TLS en el (ISS).

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/32.png)

· Habilitamos la autenticación básica.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/33.png)

· Configuramos el PegasusMail para que utilice la autentificación.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/34.png)

· Correo con autentificación básica.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/35.png)

· Error con el envío con la autentificación básica. No pude resolverlo por lo tanto no pude realizar este apartado.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_SMTP/36.png)


# hMailServer en Windows Server 2016 - Christian José Moreno Expósito #

· Primero desinstalamos el servicio SMTP.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/1.png)

· Ahora vamos a la página de hMailServer y nos lo descargamos e instalamos.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/2.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/3.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/4.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/5.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/6.png)

· Escribimos una contraseña.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/7.png)

· Instalamos las Frameworks 2.0.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/8.png)

· Finalizamos la instalación.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/9.png)

· Abrimos el hMailServer y enctramos el localhost con nuestra contraseña.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/10.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/11.png)

· Añadimos dos nuevos dominios.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/12.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/13.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/14.png)

· Establecemos una carpeta para el backup.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/15.png)

· Añadimos cuentas de los usuarios cada una con distintas configuraciones

· Ficticio 1

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/16.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/17.png)

· Ficticio 2, le añadimos un nombre.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/18.png)

· Ficticio 3, le añadimos la respuesta automática.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/19.png)

· Ficticio 4, le añadimos que reenvie a otro usuario.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/20.png)

· Añadimos nuevas zonas de busqueda en el DNS.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/21.png)

· Ahora vamos a configurar algunas opciones del servidor .

· Añadimos un rango de IP que podrán hacer envíos de mensajes.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/22.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/23.png)

· Añadimos un correo al cuan se reenviaran todos los mensajes.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/24.png)

· Modificamos el puerto del IMAP

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/25.png)

· Escribimos mensajes de bienvenida de los protocolos.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/26.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/27.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/28.png)

· Instalamos Telnet en el servidor.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/29.png)

· Comprobamos que nos tira el mensaje de bienvenida en todos los protocolos conectando por telnet.

SMPT:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/30.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/31.png)

POP3:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/32.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/33.png)

IMAP:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/34.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/35.png)

· Deshabilitamos el auto ban para que no nos banee.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/36.png)

· Nos descargamos el cliente de thunderbird y configuramos lo siguiente para conectar con el usuario.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/37.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/38.png)

· Nos salta el siguiente mensaje, le damos confirmar.

![iamge](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/39.png)

· Tuve un error al intentar entrar con los usuarios, no me dejaba iniciar sesión con ningún usuario y tenian contraseñas y nombre bien puestos. Por lo que no pude realizar las comprobaciones oportunas, pero todo debería de funcionar perfectamente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20Correo%20Electr%C3%B3nico%20en%20Windows%202016%20ServerTarea/cap_hMail/40.png)

