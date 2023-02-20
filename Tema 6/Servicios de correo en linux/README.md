# Servicio de correo en Linux - Christian José Moreno Expósito #

## SMTP ##

Lo primero que hacemos es instalar el servidor Postfix que nos distribuirá el servicio SMTP. Cuando lo estemos instalando seleccionamos "Internet Site" y le ponemos el nombre de dominio que queramos.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/1.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/2.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/3.png)

Comprobamos que esta en funcionamiento y con sus respectivos puertos funcionando.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/4.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/5.png)

Vamos a realizar una prueba de envío entre dos usuarios del sistema mediante telnet. Luego vamos a la carpeta /var/spool/mail/christian y comprobamos que se a enviado y recibido correctamente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/6.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/7.png)

Ahora nos vamos al cliente e instalamos el Evolution.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/8.png)

Lo configuramos de la siguiente manera

Ponemos el nombre de nuestro usuario, que es el nombre normal del usuario con el dominio que configuramos a la hora de instalarnos el Postfix

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/9.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/10.png)

Le especificamos la IP del servidor, el puerto y no le ponemos método de cifrado.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/11.png)

Debe quedar así:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/12.png)

Tenemos que hacer lo mismo con todas las cuentas con la que queramos hacer envíos.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/13.png)

Hacemos la prueba de envío.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/14.png)

Aquí nos muestra este error el cual solucione más adelante pero no tengo capturas, fue un error muy tipico que es que no tenia al usuario en el dominio. Pero funcionaba correctamente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/15.png)

## IMAP ##

Instalamos IMAP.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/16.png)

Comprobamos los puertos.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/17.png)

Para usar el IMAP nos vamos a descargar el SquirrelMail que en la última versión de Ubuntu lo tenemos que hacer que pillar de una página web, descomprimirlo y darle permisos porque ya no esta en los repositorios. Tenemos que utilizar estos comando en este orden:

wget https://sourceforge.net/projects/squirrelmail/files/stable/1.4.22/squirrelmail-webmail-1.4.22.zip

unzip squirrelmail-webmail-1.4.22.zip

sudo mv squirrelmail-webmail-1.4.22 /var/www/html/

sudo chown -R www-data:www-data /var/www/html/squirrelmail-webmail-1.4.22/

sudo chmod 755 -R /var/www/html/squirrelmail-webmail-1.4.22/

sudo mv /var/www/html/squirrelmail-webmail-1.4.22/ /var/www/html/squirrelmail

Para configurarlo ponemos el siguiente comando que nos abrirá los ajustes

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/18.png)

Una vez dentro lo primero que hacemos es cambiar el nombre del dominio. Pulsamos el 2, luego el 1 y añadimos el dominio que pusimos al principio en Postfix

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/19.png)

Ahora nos volvemos al menú de antes, pulsamos el 4 y tenemos que cambiar las dos primeras rutas que nos pone y la opción 11 de false a true.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/20.png)

Ahora en mi caso no me carga la página de SquirrelMail. En un principio me cargó pero al reiniciar la máquina no volvió a cargar más , volví a hacer la instalación y configuración y seguía sin funcionar. Debe ser algun problema de la máquina.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/211.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/21.png)

## POP 3 ##

Instalamos POP3:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/22.png)

Comprobamos puerto y el servicio

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/23.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/24.png)

Ahora nos tenemos que ir otra vez al Evolution y configurarlo igual que antes pero añadiendo el POP3 de la siguiente forma:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/25.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/26.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/27.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/28.png)

Ahora enviamos un mensaje de prueba y efectivamente comprobamos que se envió correctamente.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%206/Servicios%20de%20correo%20en%20linux/IMG/%C2%B429.png)
