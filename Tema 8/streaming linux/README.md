# Servidor Streaming Linux - Sergio y Christian #

Primero nos instalamos sel servicio icecast2

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/1.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/2.png)

Escogemos un nombre del servidor:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/3.png)

Elegimos una contraseña, yo las dejo por defecto:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/4.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/5.png)

En el siguiente archivo podemos modificar la siguientes lineas si lo deseamos:

<source-password>contraseña_source</source-password>

<admin-user>tu_usuario</admin-user>

<admin-password>contraseña_administrador</admin-password>

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/6.png)

Iniciamos icecast2:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/7.png)

Instalamos el codificador vorbis ices2:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/8.png)

Creamos el directorio para el codificador y copiar el fichero de configuración por defecto:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/9.png)

Editamos el fichero de configuración del codificador y establecemos los parámetros de nuestra emisora.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/10.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/11.png)

Descargamos un fichero de musica .ogg y lo copiamos en el directorio /tmp/musica

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/12.png)

Generamos la lista de reproducción:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/13.png)

Creamos el directorio ices2 y ejecutamos el codificador background:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/14.png)

Al acceder a traves de la IP nos muestra ya nuestro servicio de streaming.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/15.png)

Accedemos a la parte de administración:

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/16.png)

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/17.png)

Así queda el servicio de reproducción cuando la lista llega a su fin.

![image](https://github.com/christianjmx/SRD_christian/blob/main/Tema%208/streaming%20linux/IMG/18.png)

